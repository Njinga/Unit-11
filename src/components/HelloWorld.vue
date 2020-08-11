<template>
    <mdb-container>
        <!-- -->
        <section class="text-center white-text special-color  py-3 px-3">
            <h4 class="pt-2 pb-2 text-center"> UNIT 1: Multi-variable functions</h4>
        </section>
        <section class="text-center dark-grey-text mb-4 mt-4">
            <h4 class="font-weight-bold pb-4 text-center">
                <mdb-icon icon="marker" size="lg" class="mr-3" />
                Learning outcomes
                <mdb-icon icon="graduation-cap" size="lg" class="ml-3" />
            </h4>
            <mdb-row class="text-left">
                <!-- Choose appropriate mdb-col  -->
                <mdb-col class="text-left w-responsive mx-auto m-3">
                    <p>
                        <ul>
                            <li>
                                <strong><em>Identify</em></strong> and <strong><em>sketch</em></strong> the domain and range of
                                functions of two variables.
                            </li>
                            <li><strong><em>Derive</em></strong> revenue and profit functions from given cost data and demand schedule.</li>
                            <li>
                                <strong><em>Define</em></strong> and <strong><em>compute</em></strong> the first and second order partial derivatives of functions
                                of two or more variables.
                            </li>
                            <li>
                                <strong><em>Use</em></strong> partial derivatives to <strong><em>calculate</em></strong>
                                marginal quantities, such as cost, profit,
                                revenue, productivity and utility, and interpret the results.
                            </li>
                            <li>
                                <strong><em>Use</em></strong> partial derivatives to <strong><em>determine</em></strong>
                                whether products are complementary or substitutes.
                            </li>
                            <li>
                                <strong><em>Construct</em></strong> and <strong><em>solve</em></strong> unconstrained optimization problems, defined as functions of two
                                variables, using the second partial derivative test.
                            </li>
                            <li>
                                <strong><em>Formulate</em></strong> and <strong><em>solve</em></strong> constrained optimization problems using the substitution method
                                and the method of Lagrange Multipliers.
                            </li>
                            <li>
                                <strong><em>Use</em></strong> partial derivatives to <strong><em>solve</em></strong> a class of optimization problems with applications in
                                business and economics. Examples to include
                            
                            <ul>
                                <li>	Minimising costs subject to production quotas.</li>
                                <li>	Maximising utility subject to budgetary constraints</li>
                                <li> Maximising production subject to a cost constraint. </li>
                            </ul>
                                </li>
                        </ul>
                    </p>
                </mdb-col>

                <mdb-col class="text-left w-responsive mx-auto m-3">

                </mdb-col>   
            </mdb-row>
        </section>
        <hr />
        <!--PARTIAL DERIVATIVES START HERE-->
        <section class="text-center dark-grey-text mb-4 mt-4">
            <h4 class="font-weight-bold pb-4 text-center">Introduction</h4>
            <mdb-row>
                <!-- Choose appropriate mdb-col  -->
                <mdb-col>
                </mdb-col>
            </mdb-row>
        </section>
        <hr />
        <section class="text-justify dark-grey-text mb-4">
            <h4 class="font-weight-bold pb-4 text-center"> Partial Derivatives</h4>
            <mdb-row>
                <!-- Choose appropriate mdb-col  -->
                <mdb-col text-justify w-responsive mx-auto m-3>

                    <h4 class=" h4 font-weight-bold pb-4 text-center shadow z-depth-5"> Application of partial derivatives</h4>
                    <br />
                    <br />
                    <p class="font-weight-bold text-center">
                        MS202<br/>
                        Marginal productivity (Cobb-Douglas)
                    </p>
                    <br/>
                    <p class="text-justify size20 red-text bg-grey-lighten-4">
                        Cobb-Douglas function
                    </p>
                   

                    <p class="blue-text">What is Cobb-Douglas equation?</p>
                    <div class="note note-primary shadow rounded border border-light z-depth-5">
                        <p class="ml-3 mr-3">
                            In economics, the Cobb-Douglas function is a  production function,
                            used to represent relationship between the amounts of two or more
                            inputs (particularly physical <strong>capital</strong> and <strong>labour</strong>)
                            and the amount of output that can be produced by those inputs.
                        </p>
                    </div>
                    <br />
                    <br />
                    <div>
                        In its most standard form for production of a single good with two factors,
                        the function is
                        <div v-katex:display="'f(x,y) = Ax^\\beta y^\\alpha '"></div>
                        <div>
                        -<span v-katex="'f (x,y)'"></span> is the total production<br/>
                        -<span v-katex="'x'"></span>  is the quantity of labour.<br/>
                        -<span v-katex="'y'"></span> is the quantity of capital.<br/>
                        -<span v-katex="'A'"></span> is a positive constant.<br/>
                        -<span v-katex="'\\beta'"></span> and <span v-katex="'\\alpha'"></span> are constants between 0 and 1.
                        </div>


                    </div>
                    <br />
                    <br/>
                    <p class="text-justify size20 red-text bg-grey-lighten-4">
                        Marginal Productivity
                    </p>
                    
                    
                    <p class="blue-text">What is marginal product?</p>
                    <div class="note note-primary shadow rounded border border-light z-depth-5">
                        <p class="ml-3 mr-3">
                            Marginal product is the change in total production, when there is an
                            infinitesimal change in the inputs. Marginal product is the first derivative
                            of the production function with respect to an input. The term <em>marginal</em> is
                            used because it measures the change of production with a small change of
                            either the capital or labour
                        </p>
                    </div>
                    <br/>
                    <br />
                    <div>
                        <p>
                            The marginal product of labour is defined as
                        </p>
                        <div v-katex:display="'\\frac{\\partial f}{\\partial x} '"></div>
                    </div>
                    <p>
                        and it measures the change of production with a small change of labour
                        Similarly, the marginal product of capital is defined as
                    </p>
                    <div v-katex:display="'\\frac{\\partial f}{\\partial y} '"></div>
                    <p>
                        and it measures the change of production with a small change of capital.
                    </p>
                    <br />
                    <div>
                        <p class="text-justify size20 red-text bg-grey-lighten-4">
                            Example on marginal productivity
                        </p>
                        <!--Example 1-->
                        <p class="green-text">Example (1)</p>
                        <p>
                            A certain country's production is described by the function
                        </p>
                        <div class="text-center" style="margin-bottom:20px;">
                            <span v-katex="'f(x,y)= \\space'"></span><span v-katex="example1Function"></span>
                        </div>
                        
                        units, when <span v-katex="'x'"></span> units of labour and <span v-katex="'y'"></span> units of capital were used
                        <br /><br />

                        <ul style="list-style-type:lower-alpha;">

                            <li>
                                What is the marginal productivity of labour and the marginal
                                productivity of capital when the amounts spent on labour and capital are
                                81 units and 625 units,respectively?
                            </li>
                            <li>
                                Should the government prioritise capital investment over increased
                                spending on labour at this time in order enhance the country's
                                productivity?
                            </li>
                        </ul>
                        <br />
                        <br />
                        <p class="text-justify size20 red-text bg-grey-lighten-4">
                            Finding marginal productivity of labour
                        </p>

                        <p>
                            The marginal productivity of labour when the amounts spent on labour
                            and capital are <span v-katex="'x'"></span> and <span v-katex="'y'"></span> units, respectively, is computed from the partial
                            derivative of <span v-katex="'f'"></span> with respect to <span v-katex="' x'"></span>  as
                        </p>
                        
                        <div class="text-center" style="margin-bottom:20px;">
                            <span v-katex="'\\frac{\\partial f}{\\partial x}=f_{x}(x,y)= \\space'"></span><span v-katex="fxFunction"></span>
                        </div>
                        <p>
                            When <span v-katex="'x = 81 '"></span> and <span v-katex="'y = 625'"></span> the required marginal productivity of labour is
                        </p>
                        <div v-katex:display="'f_x(81, 625) = 400\\left(\\frac{625}{81}\\right)^{\\frac{3}{4}} = 400\\left(\\frac{125}{27}\\right)^{\\frac{3}{4}} =  1851.85'"></div>
                        <p>
                            The marginal productivity of labour is 1851.85 units per unit increase in
                            labour expenditure (with capital expenditure held fixed at 625 units).
                        </p>
                    </div>
                    <br />
                    <br/>
                    <div>
                        <p class="text-justify size20 red-text bg-grey-lighten-4">
                            Finding marginal productivity of capital
                        </p>

                        <p>
                            The marginal productivity of capital when the amounts spent on labour
                            and capital are <span v-katex="'x'"></span>  and <span v-katex="'y'"></span>  units, respectively,
                            is computed from the partial derivative of <span v-katex="'f'"></span>  with respect to <span v-katex="'y'"></span>  as
                        </p>
                        <div class="text-center" style="margin-bottom:20px;">
                            <span v-katex="'\\frac{\\partial f}{\\partial y}=f_{y}(x,y)= \\space'"></span><span v-katex="fyFunction"></span>
                        </div>
                        <p>
                            When <span v-katex="'x = 81 '"></span> and <span v-katex="'y = 625'"></span> the required marginal productivity of capital is
                        </p>
                        <div v-katex:display="'f_y(81, 625) = 1200\\left(\\frac{81}{625}\\right)^{\\frac{1}{4}} = 1200\\left(\\frac{3}{5}\\right)^{\\frac{1}{4}} = 720'"></div>
                        <p>
                            The marginal productivity of capital is 720 units per unit increase in capital expenditure (with labour expenditure held fixed at 81 units).
                        </p>
                        <br /><br />
                        <div>
                            <p class="text-justify size20 red-text bg-grey-lighten-4">
                                Concluding from results
                            </p>
                            The results are
                            <p class="ml-5">
                                Marginal productivity of labour = 1851.85<br />
                                Marginal productivity of capital = 720
                            </p>
                            The results indicate that a unit increase in labour expenditure results in a
                            greater increase in productivity than a unit increase in capital expenditure
                            would have.<br />

                            <p>
                                Therefore, the government can be advised to spend
                                more on labour rather than on capital.
                            </p>

                        </div>
                    </div>
                </mdb-col>
            </mdb-row>
        </section>   
        <!--THE  END OF PARTIAL DERIVATIVES-->
    </mdb-container>
</template>
<script>
    import 'katex/dist/katex.min.css';
    import katex from 'katex/dist/katex.mjs'; 

    import nerdamer from 'nerdamer/nerdamer.core.js'
    import 'nerdamer/Algebra.js'
    import 'nerdamer/Calculus.js'
    import 'nerdamer/Solve.js'

    import { mdbContainer, mdbRow, mdbCol, mdbIcon } from "mdbvue";


    export default {
        name: "HelloWorld",
        components: {
            mdbContainer,
            mdbRow,
            mdbCol,
            mdbIcon
        },
        data() {
            return {
                answer: undefined,
                working: undefined,
                example1Function: undefined,
                fxFunction: undefined,
                fyFunction: undefined,
                answerVisibility: { visibility: false },
                workingVisibility: { visibility: false }
            }
        },
        beforeMount() {
            let initilizerVariable = this.generateRandomFunction();
            //this.example1Function = this.createFunction();
            this.example1Function = initilizerVariable[0];
            this.fxFunction = initilizerVariable[1];
            this.fyFunction = initilizerVariable[2];
            this.answer = this.unconstrainedSolution()[1];
            this.working = this.unconstrainedSolution()[0]

        },
        methods: {
            removeAsterix() {
            },
            update_element(element, value) {
                katex.render(value, this.$refs[`${element}`], {
                    throwOnError: false
                });
            },
            //Get random integer between min and max
            generateRandomInteger(min, max) {
                return Math.floor(min + Math.random() * (max + 1 - min))
            },
            isInt(num) {
                if (typeof num !== 'number')
                    return false;
                return !isNaN(num) &&
                    parseInt(Number(num)) == num &&
                    !isNaN(parseInt(num, 10));
            },
            plusOrMinus(nn) {
                let str = ' ';
                if (nn === 1) {
                    str = ` + `;
                }
                else if (nn === -1) {
                    str = ` - `;
                }
                else if (nn > 0) {
                    str = ` + ` + Math.abs(nn);
                } else {
                    str = ` - ` + Math.abs(nn);
                }
                return str
            },
            plusOrMinusNew(nn) {
                let str = ' ';
                if (nn === 1) {
                    str = `  `;
                }
                else if (nn === -1) {
                    str = ` - `;
                }
                else if (nn > 0) {
                    str = `  ` + Math.abs(nn);
                } else {
                    str = ` - ` + Math.abs(nn);
                }
                return str
            },

            plusOrMinusForEquation(nn, varx) {
                let str = ``;

                if (nn === 1) {
                    str = ` + ` + varx;
                }
                else if (nn === -1) {
                    str = ` - ` + varx;
                }
                else if (nn > 0) {
                    str = ` + ` + Math.abs(nn) + varx;
                }
                else if (nn < 0) {
                    str = ` - ` + Math.abs(nn) + varx;
                } else {
                    str = ` `
                }

                return str
            },
            isOdd(num) {
                if (typeof num === 'number') {
                    return ((num % 2) === 1) || ((num % 2) === -1) ? true : false;
                }
                else {
                    throw 'Not a number';
                }
            },
           

            generateRandomFunction() {

                let A = this.generateRandomInteger(1500, 2500);
               // let B = this.generateRandomInteger(70, 85);
                //let C = this.generateRandomInteger(600, 650);
                let w = Math.random();
                let k = Math.random();

                let f = `${A}x^{${w}}y^{${k}}`;
                let fx = `${A}(${w})x^{${w - 1}}*y^{${k}}`;
                let fy = `${A}x^{${w}}*(${k})y^{${k-1}}`;
                let fxAnswer = nerdamer(`diff(${f},x)`);
                let fyAnswer = nerdamer(`diff(${f},y)`);

                return [f, fx, fy, fxAnswer, fyAnswer];
            },

            getFunction() {
                return this.example1Function;
            },
            createFunction() {
                //Come back here!
                //return `x^2 -4*x + 3*y^2-18*y+5`; 
                //  return  `x^3 + 3*x^2 + y^3 - 3*y^2 - 8`; 
                //let choice = ["Maximum", "Minimum", "Opposite"]; 
                let choice = ["Maximum2", "Minimum2", "Opposite"];
                let typeNum = choice[Math.floor(Math.random() * choice.length)];//Randomly choosing type 
                return this.generateQuadratic2(typeNum);
            },
            handleClickNewExample() {
                //   let choice = ["Maximum", "Minimum", "Opposite"]; 
                // let choice = ["Maximum2", "Minimum2", "Opposite"];
                // let typeNum = choice[Math.floor(Math.random() * choice.length)];//Randomly choosing type 
                //this.example1Function = this.generateQuadratic2(typeNum);
                this.example1Function = this.generateRandomFunction();
                this.answer = this.unconstrainedSolution()[1];
                this.working = this.unconstrainedSolution()[0];
                this.update_element('answer', this.answer);
                this.update_element('working', this.working);
                this.update_element('example1Function', this.example1Function);
                this.update_element('fxFunction', this.fxFunction);
                this.update_element('fyFunction', this.fyFunction);
            }
            
        }
    }
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>



.headingUnd{
    border-bottom: 2px solid currentColor;
    display: inline-block;
    line-height: 0.85;
    text-shadow:
    2px 2px white,
    2px -2px white,
    -2px 2px white,
    -2px -2px white;
}
    .size20 {
        font-size:20px;
        
    }

    .bg-grey-lighten-4 {
        background-color:#f5f5f5;
    }


</style>