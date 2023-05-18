# BEM
# 1 задание 
<!-- блоки -->
head
body
hands
<!--элементы  -->
head__brain
head__eyes
body__hair
body__belly-button
hands__hand
hand__nails
hand__fingers
<!-- модификаторы -->
head__eyes--color-blue
body__hair--length-short
hands__hand--tattoo
# 2-4 задание
![Alt text](header.png?raw=true "Header")
```
<!-- header -->
header.header>a.logo>img.logo__img^nav.nav>ul.sections>li.sections__li*4>a.sections__link^^ul.links>li.links__li*2>a.links__link^li.links__li--button>a.links__link
```
![Alt text](form.png?raw=true "Form")
```
<!-- форма -->
form.form-lesson>legend.form-lesson__legend>span.form-lesson__header^input.form-lesson__input*2+button.form-lesson__btn
```
![Alt text](card.png?raw=true "Card")
```
<!-- карточка -->
li.card>img.card__img+p.card__content
```
![Alt text](footer.png?raw=true "Footer")
```
<!-- footer -->
footer.footer>ul.footer__contact>li.footer__phone+li.footer__time+li.social-links>a.social-links__link*3>img.social-links__img^^^ul.footer__legal>li.footer__link-item*5>a.footer__link^^ul.footer__app>li.footer__app-item*2>a.footer__app-img
```