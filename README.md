между секциями ставим паддинги потмоу что не должно быть путоты
.menu-item:not(:last-child){
margin-right: 30px
}

.menu-item:nth-child(even) (четные){

}

.menu-item:nth-child(odd) (не четные){

}

@import "./utils/\_vars";
@import "./utils/base";
@import "./utils/placeholders";
@import "./utils/mixins";
@import './components/header-mobile';
@import "./components/page-header";
@import "./components/hero";
@import "./components/features";
@import "./components/what-are-we";
@import "./components/our-team";
@import "./components/clients";
@import "./components/footer";
@import "./components/portfolio";
@import "./components/animation";
@import "./components/modal-form";
@import "components/footer-form";

.card-portfolio:nth-last-child(-n+3) {
@media(min-width:480px){
margin-bottom: 0;
}
@media(min-width:768px){
margin-bottom: 30px;
}
@media(min-width:1200px){
margin-bottom: 0;

    }

}

.card-portfolio:nth-last-child(3n+1) {
@media(min-width:480px){
margin-right: 0;
}
@media(min-width:768px){
margin-right: 0;
}
@media(min-width:1200px){
margin-right: 0;
margin-left: 15px;

    }

}

.card-portfolio:nth-child(2n){
@media(min-width:768px){
margin-right:0
}
}
.card-portfolio:nth-child(2n+1) {
@media(min-width:768px) {
margin-right: 15px;
}
}

.card-image-portfolio {
display: block;
@media(min-width:480px){
margin-right: 0;
width: 450px;
height: 294px;
}
@media(min-width:1200px){
display: block;
}

}

.card-portfolio:nth-child(2n+1){
@media(min-width:480px){
margin-right: 0;
margin-left:0;
}
@media(min-width:768px){
margin-right: 15px;
margin-left:0;
}
@media(min-width:1200px){

    }

}
