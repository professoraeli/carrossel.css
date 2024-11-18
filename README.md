# carrossel.css
padding: 1em 2.2em;
    color: var(--branco);
    font-weight: 700;
    text-decoration: none;
}

@media screen and (min-width: 1024px) {
    .carrossel__titulo {
        font-size: 26px;
    }

    .swiper-pagination {
        margin: 2em 0 3em 0;
    }

    .swiper {
        width: 60%;
    }

    .swiper-button-prev,
    .swiper-button-next {
        display: block;
        top: 60%;
    }
    .card {
        width: 40%;
        margin: 2em auto;
    }
}

@media screen and (min-width: 1728px) {
    .carrossel__container {
        display: flex;
        margin: 0 20vw 3em 20vw;
        align-items: center;
    }

    .swiper-pagination {
@@ -121,10 +115,6 @@
        font-size: 16px;
    }

    .descrição {
        margin-right: 2em;
    }
    .card {
        width: 60%;
        margin-left: 3em;
