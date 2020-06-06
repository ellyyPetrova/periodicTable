 <!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" type="text/css" href="style.css">
        <title> Periodic Table of Elements, in CSS! </title> 
		<style>
		body{
    font-size: 16px;
}
section{
    width: 1500px;
    max-width: 100%;
    margin: 0px auto;
}
#container{
    width: 1400px;
}
.box{
    border: 3px solid black; 
    max-width: 50px;
    max-height: 50px; 
    padding: 10px;
    line-height: 50px; 
    text-align: center; 
    font-size: 1.64em;
}

#panelOne{
    float: left; 
	background : #bf3737;
}

#panelTwo{
    float: left; 
    position: relative; 
    top: 76px; 
	background : #b28727;
}

.panelThree{
    float: left; 
    position: relative; 
    top: 228px; 
	background : #f2c152;
}

.panelFour{
    float: left; 
    position: relative; 
    top: 76px;
    background : #30bef2;	
}

#panelFive{
    float: left;
    background : #8ece8f;	
}

#lowerContainer{
    float: right; 
    margin-top: 20px;
	background : #a85a94;
}

.bottom{
    float: left; 
}
</style>
    </head> 
    <body>
	
        <section>
		<ul>
		<li> Non metal </li>
		<li> Alkali metal </li>
		<li> Alkaline earth metal </li>
		<li> Transition metal </li>
		<li> Metal </li>
		<li> Metalloid </li>
		<li> Halogen </li>
		<li> Noble gas </li>
		<li> Lanthanide </li>
		<li> Actinide </li>
		</ul>
		
            <div id="container">
            <div id="panelOne">
                <div class="box"> H </div> 
                <div class="box"> Li </div> 
                <div class="box"> Na </div> 
                <div class="box"> K </div> 
                <div class="box"> Rb </div> 
                <div class="box"> Cs </div> 
                <div class="box"> Fr </div> 
            </div>
            <div id="panelTwo">
                <div class="box"> Be </div> 
                <div class="box"> Mg </div> 
                <div class="box"> Ca </div> 
                <div class="box"> Sr </div> 
                <div class="box"> Ba </div> 
                <div class="box"> Ra </div> 
            </div>
            <div class="panelThree">
                <div class="box"> Sc </div> 
                <div class="box"> Y </div> 
                <div class="box"> La </div> 
                <div class="box"> Ac </div> 
            </div>
            <div class="panelThree">
                <div class="box"> Ti </div> 
                <div class="box"> Zr </div> 
                <div class="box"> Hf </div> 
                <div class="box"> Rf </div> 
            </div>
            <div class="panelThree">
                <div class="box"> V </div> 
                <div class="box"> Nb </div> 
                <div class="box"> Ta </div> 
                <div class="box"> Db </div> 
            </div>
            <div class="panelThree">
                <div class="box"> Cr </div> 
                <div class="box"> Mo </div> 
                <div class="box"> W </div> 
                <div class="box"> Sg </div> 
            </div>
            <div class="panelThree">
                <div class="box"> Mn </div> 
                <div class="box"> Tc </div> 
                <div class="box"> Re </div> 
                <div class="box"> Bh </div> 
            </div>
            <div class="panelThree">
                <div class="box"> Fe </div> 
                <div class="box"> Ru </div> 
                <div class="box"> Os </div> 
                <div class="box"> Hs </div> 
            </div>
            <div class="panelThree">
                <div class="box"> Co </div> 
                <div class="box"> Rh</div> 
                <div class="box"> Ir </div> 
                <div class="box"> Mt </div> 
            </div>
            <div class="panelThree">
                <div class="box"> Ni </div> 
                <div class="box"> Pd </div> 
                <div class="box"> Pt </div> 
                <div class="box"> Ds </div> 
            </div>
            <div class="panelThree">
                <div class="box"> Cu </div> 
                <div class="box"> Ag </div> 
                <div class="box"> Au </div> 
                <div class="box"> Rg </div> 
            </div>
            <div class="panelThree">
                <div class="box"> Zn </div> 
                <div class="box"> Cd </div> 
                <div class="box"> Hg </div> 
                <div class="box"> Cn </div> 
            </div>
            <div class="panelFour">
                <div class="box"> B </div> 
                <div class="box"> Al </div> 
                <div class="box"> Ga </div> 
                <div class="box"> In </div> 
                <div class="box"> Tl </div> 
                <div class="box"> Uut </div> 
            </div>
            <div class="panelFour">
                <div class="box"> C </div> 
                <div class="box"> Si </div> 
                <div class="box"> Ge </div> 
                <div class="box"> Sn </div>
                <div class="box"> Pb </div> 
                <div class="box"> Fl </div>  
            </div>
            <div class="panelFour">
                <div class="box"> N </div> 
                <div class="box"> P </div> 
                <div class="box"> As </div> 
                <div class="box"> Sb </div> 
                <div class="box"> Bi </div> 
                <div class="box"> Mc </div> 
            </div>
            <div class="panelFour">
                <div class="box"> O </div> 
                <div class="box"> S </div> 
                <div class="box"> Se </div> 
                <div class="box"> Te </div> 
                <div class="box"> Po </div> 
                <div class="box"> Lv </div> 
            </div>
            <div class="panelFour">
                <div class="box"> F </div> 
                <div class="box"> Cl </div> 
                <div class="box"> Br </div> 
                <div class="box"> I </div> 
                <div class="box"> At </div> 
                <div class="box"> Ts </div> 
            </div>
            <div id="panelFive">
                <div class="box"> He </div> 
                <div class="box"> Ne </div> 
                <div class="box"> Ar </div> 
                <div class="box"> Kr </div> 
                <div class="box"> Xe </div> 
                <div class="box"> Rn </div> 
                <div class="box"> Og </div> 
            </div>
        </div>
        <div id="lowerContainer">
            <div class="bottom">
                <div class="box"> Ce </div> 
                <div class="box"> T </div> 
            </div>
            <div class="bottom">
                <div class="box"> Pr </div> 
                <div class="box"> Pa </div> 
            </div>
            <div class="bottom">
                <div class="box"> Nd </div> 
                <div class="box"> U </div> 
            </div>
            <div class="bottom">
                <div class="box"> Pm </div> 
                <div class="box"> Np </div> 
            </div>
            <div class="bottom">
                <div class="box"> Sm </div> 
                <div class="box"> Pu </div> 
            </div>
            <div class="bottom">
                <div class="box"> Eu </div> 
                <div class="box"> Am </div> 
            </div>
            <div class="bottom">
                <div class="box"> Gd </div> 
                <div class="box"> Cm </div> 
            </div>
            <div class="bottom">
                <div class="box"> Tb </div> 
                <div class="box"> Bk </div> 
            </div>
            <div class="bottom">
                <div class="box"> Dy </div> 
                <div class="box"> Cf </div> 
            </div>
            <div class="bottom">
                <div class="box"> Ho </div> 
                <div class="box"> Es </div> 
            </div>
            <div class="bottom">
                <div class="box"> Er </div> 
                <div class="box"> Fm </div> 
            </div>
            <div class="bottom">
                <div class="box"> Tm </div> 
                <div class="box"> Md </div> 
            </div>
            <div class="bottom">
                <div class="box"> Yb </div> 
                <div class="box"> No </div> 
            </div>
            <div class="bottom">
                <div class="box"> Lu </div> 
                <div class="box"> Lr </div> 
            </div>
            <div class="bottom">
                <div class="box"> La </div> 
                <div class="box"> Ac </div> 
            </div>
        </div>
        </section>
		
		   
    </body>
</html>
