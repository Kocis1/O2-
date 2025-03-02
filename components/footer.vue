<script setup>
</script>

<template>
	<div class="container">
		<div class="container__inner">
			<div class="footer__top">
				<div class="footer__top__content">
					<div class="footer__top__content-logo">
						<img
							src="/public/Новая папка/logo.png"
							alt="BottomLogo"
						>
					</div>
					<div class="footer__top__content-input">
						<input
							type="text"
							placeholder="Введите свой Email и получите скидку"
						>
						<button class="footer__top__content-button">
							<img
								src="/public/svg/Send r_15.svg"
								alt="Send"
							>
						</button>
					</div>
					<div class="footer__top__content-button">
						<button>
							<img
								src="/public/Новая папка/Facebook.png"
								alt=""
							>
						</button><button>
							<img
								src="/public/Новая папка/Facebook.png"
								alt=""
							>
						</button>
						<button>
							<img
								src="/public/Новая папка/Facebook.png"
								alt=""
							>
						</button>
					</div>
				</div>
			</div>
			<div class="footer__center">
				<ul class="footer__center-ul">
					Покупателям<li>Наша почта</li>
					<li>Оплата и доставка</li>
					<li>Вопросы и ответы</li>
				</ul>
				<ul class="footer__center-ul">
					Издательство<li>О компании</li>
					<li>Авторам</li>
					<li>Вакансии</li>
					<li>Контакты</li>
				</ul>
				<ul class="footer__center-ul">
					Книги<li>Все категории</li>
					<li>Бестселлеры</li>
					<li>Новинки</li>
					<li>Скидки и акции</li>
				</ul>
				<ul class="footer__center-ul">
					Прайс-лист<li><img></li>
				</ul>
				<ul class="footer__center-ul">
					Телефон и Email<li>market@estatut.ru</li>
					<li>8 (968) 660-65-50</li>
				</ul>
			</div>
			<div class="footer__bottom">
				ewq
			</div>
		</div>
	</div>
</template>

<style lang="css" scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');
.container{
    max-width: 1366px;
    margin: 0 auto;
}
.container__inner{
    max-width: 1140px;
    margin:0 auto;
}
.footer__top__content{
    display: flex;
    justify-content: space-between;
    height: 40px;
}
.footer__top__content-input{
    max-width: 443px;
    display: flex;
    border: 1px solid black;
}
.footer__top__content-input>input{
    width: 383px;
    padding: 15px 10px;
}
.footer__top__content-input>button{
    width: 50px;
    height: 40px;
    background-color: #FF5C00;
    display: flex;
    justify-content: center;
    align-items: center;
    }
    .footer__top__content-button{
        width: 150px;
        display: flex;
        justify-content: space-between;
    }
.footer__center{
    display: flex;
    justify-content: space-between;
}
</style>
