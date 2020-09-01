#navContainer {
    background-color: #231814;
}
html {
    background-image: url("../images/background.gif");
    background-repeat-x: repeat;
}
/*  Wrapper for 80% width  */
#wrapper {
    width: 80% !important;
    margin-left: 10% !important; 
    margin-right: 10% !important;
    font-family: Verdana !important;
    color: #221811 !important;
    background-color: #FCEBB6 !important;
    box-shadow: 1px 1px 1px grey;
}
/* Some common style for all the pages */
h1 {
    font-family: Verdana !important;
    color: #221811 !important;
    background-color: #D2B48C !important; 
    line-height: 200% !important;  
    padding-left: 20px !important;
    margin: 0px !important;
    font-weight: bold !important;
}
h2 {
    font-family: Georgia, serif !important;
    font-weight: bold !important;
    padding: 2%;
}
ul {
    padding-left: 2%;
}
nav {
    text-align: center;
    font-weight: bold;
}
nav a {
    color: #FCEBB6;
}
address {
        padding-left: 2%;
}
nav > ul {
    list-style-type: none;
}
/* Footer Style common for all Pages */
footer
{
    font-family: Verdana;
    font-style: italic;
    font-size: 0.60em;
    color: #221811;
    text-align: center;
    background-color: #D2B48C;
    border-top: #231b13 solid;
    border-bottom:#231b13 solid 1px;
}
/* Menu Page - Container for Table */
#tableContainer {
    width: 90%;
    margin-left: auto;
    margin-right: auto;
    border-spacing: 0;
    margin-bottom: 2%;
}
/* Menu Page - color odd rows using nthoftype pseudo class */
#tableContainer tr:nth-of-type(odd){
    background-color: #D2B48C !important;
}
/* Menu Page - td text align center */
.tdTextCenter {
    text-align: center;
}
.menuData {
    padding-left: 5% !important;
}
.musicData {
    padding-left: 5%;
}
#menuH2 {
    padding-left: 6%;
}
.row {
    margin-left: 0px !important;
    margin-right: 0px !important;
}
.row div {
    padding: 0px;
}
.p-content {
    padding: 20px !important;
}
.addressClass {
    padding-left: 20px !important;    
}
/* Index Page - telephone tag remove link */
#telId {
    text-decoration: none;
    color: #221811;
}
/* Music Page - Division for January and February */
.division {
    display: block;
    background-color: #D2B48C;
    border-bottom: 1px solid;
    padding-left: 5%;
}
/* Music Page - Table style class */
.musicTableClass {
    border-spacing: 0;
    margin-left: auto;
    margin-right: auto;
    width: 80%;
}
.musicTableClass td {
    padding-bottom: 2%;
}
/* Job Page - Style for froms */
form {
        padding-left: 10%;
        padding-bottom: 5%;
}
label {
    float: left;
    margin-top: 5%;
    text-align: left;
}
input, textarea {
    margin-top: 10px;
}
.text-right{
    text-align: right;
}
/* Job Page - Style for header */
#jobsHeader {
    border-bottom:#231b13 solid 15px; 
}
/* Media query */
@media only screen and (min-width: 768px){
    label {
        float: right !important;
        text-align: right !important;
        padding-right: 10% !important;
    }
}
fieldset { 
    display: block !important;
    margin-left: 2px !important;
    margin-right: 2px !important;
    padding-top: 0.35em !important;
    padding-bottom: 0.625em !important;
    padding-left: 0.75em !important;
    padding-right: 0.75em !important;
    border: 2px groove !important;
}
.columnGear {
    float: left;
    /*margin-left: 2%;*/
    margin-left: 2%;
}
.rowGear:after {
    content: "";
    display:table;
    clear: both;
    margin-bottom: 2%;
    
}
.innerDiv {
    float: left;
    margin-left: 1%;
    width:75%;
}
.gearForm {
    padding-left: 0%;
    padding-bottom: 0%;
}
.columnMusicPhpImg {
    float: left !important;
    /*margin-left: 2%;*/
    margin-left: 20% !important;
}
.columnMusicPhp {
    float: left !important;
    /*margin-left: 2%;*/
    margin-left: 2% !important;
}

.rowMusicPhp:after {
    content: "" !important;
    display:table !important;
    clear: both !important;
    margin-bottom: 2% !important;
}

.cartTable {
    margin-left: 19% !important;
    margin-top: 1%;
    text-align: center !important;
    width: 40%;
}
.cartTable tr:nth-of-type(odd){
    background-color: #D2B48C !important;
}
#h5Gear {
   margin-left: 40%;
   margin-top: 10%;
}
.cartTR {
    padding: 15% 15% 15% 15%;
}
.cartbutton1 {
    margin-top: 5%;
    margin-left: 30%;
    margin-bottom: 2%;
}
.cartButton2 {
    margin-left: 1%;
}
.rowCart:after {
    content: "" !important;
    display:table !important;
    clear: both !important;
    margin-bottom: 2% !important;
}
.columnCart {
    float: left !important;
    margin-left: 2% !important;
}
 .month{
box-shadow: 1px 1px 1px #888888;
background: #D2B48C;
border-bottom: 1px solid;
padding-left: 40px;
 }
  .month-content{
 padding-left: 180px;
 }
.month-content td{
     vertical-align: top;
     padding-left: 10px;
         font-size :15px;
}
.month-content img{
height:50px; width:50px;;
}
