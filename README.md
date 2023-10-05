## Выполняется макет по <a href='https://www.figma.com/file/yvEOdkbyTWFRZCv2JuF3sU/InternoS?node-id=2%3A264&mode=dev'>ссылке</a>

/_ ====================== header ======================== _/

header.header>(a.logo>img)+nav.nav>ul.nav-list>li.nav-item\*5>a

/_ ====================== banner ======================== _/

section.banner>h1.banner-title+button.bunner-btn

/_ ====================== features ======================== _/

section.features>ul.features-list>li.fetures-item\*3>h3+p

/_ ====================== project ======================== _/

section.project>(div.wrap>h2.project-title+p.project-text+button)+img

/_ ====================== brand ======================== _/

section.brand>ul.brand-list>li.brand-item\*5>svg[width="" height=""]>use[href="./img/sprite.svg#icon_1"]

/_ ====================== projects ======================== _/

section.projects>(h2.projects-title+p.projects-text)+ul.projects-list>li.projects-item\*4>(img+h3+p)

/_ ====================== footer ======================== _/

footer.footer>(div.wrap>div.footer-info>((a>img.footer-logo)+p.footer-text)+ul.social-list>li.social-item\*5>svg[width="" height=""]>use[href="./img/sprite.svg#icon_social_1"])+div.footer-copyright>p
