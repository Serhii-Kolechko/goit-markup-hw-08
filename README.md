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
