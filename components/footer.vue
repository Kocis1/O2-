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
				<div class="footer__center-container">
					<ul class="footer__center-ul">
						<li>Покупателям</li>
						<li>Наша почта</li>
						<li>Оплата и доставка</li>
						<li>Вопросы и ответы</li>
					</ul>
					<ul class="footer__center-ul">
						<li>Издательство</li>
						<li>О компании</li>
						<li>Авторам</li>
						<li>Вакансии</li>
						<li>Контакты</li>
					</ul>
					<ul class="footer__center-ul">
						<li>Книги</li>
						<li>Все категории</li>
						<li>Бестселлеры</li>
						<li>Новинки</li>
						<li>Скидки и акции</li>
					</ul>
					<ul class="footer__center-ul">
						<li>Прайс-лист</li>
						<li><img></li>
					</ul>
					<ul class="footer__center-ul">
						<li>Телефон и Email</li>
						<li>market@estatut.ru</li>
						<li>8 (968) 660-65-50</li>
					</ul>
				</div>
			</div>
			<div class="footer__bottom">
				<div class="footer__bottom-start">
					<span class="footer__bottom-start--content">© 2020 Издательство «Статут»</span>
				</div>
				<div class="footer__bottom-end">
					<div class="footer__botom-end--content">
						<div class="footer__botom-end--content--container">
							<span>ул. Лобачевского, 92, корп. 2 119454, г. Москва</span>
							<span>Политика конфиденциальности</span>
							<span>Договор оферты</span>
						</div>
					</div>
				</div>
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
.footer__top{
	margin-top: 20px;
	height: 90px;
	border-color: #282F3626;
	background-color: #282F3626;

}
.footer__top__content{
    display: flex;
    justify-content: space-between;
	align-items: center;
	padding-top: 30px;

}
.footer__top__content-input{
	width: 443px;
	height: 40px;
    display: flex;
    border: 1px solid black;
}
.footer__top__content-input>input{
    width: 393px;
    padding: 15px 10px;
}
.footer__top__content-input>button{
    width: 50px;
    height: 37.5px;
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
	margin-top: 45px;
}
.footer__center-container{
display: flex;
border-bottom: 1px solid #282F3626;
margin-bottom: 65px;

}
.footer__center-ul{
	margin-right: 30px;
	width: 165px;
}
.footer__center-ul>li:first-of-type{
	margin-bottom: 20px;

	font-weight: 500;
}
.footer__center-ul>li{
	font-family: Roboto;
font-weight: 400;
font-size: 14px;
line-height: 20px;
letter-spacing: 0px;
padding-bottom: 15px;

}
.footer__bottom{
	margin-top: 40px;
	display: flex;
	justify-content: space-between;
}
.footer__botom-end--content--container{
	max-width: 945px;
	display: flex;
	justify-content: space-between;
}
.footer__botom-end--content--container>span:first-child{
	padding-right: 67px;
}
.footer__botom-end--content--container>span:last-child{
	margin-left: 30px;
}.footer__bottom-start~span{
	font-family: Roboto;
font-weight: 400;
font-size: 14px;
line-height: 20px;
letter-spacing: 0px;
}
.footer__bottom-end{
	font-family: Roboto;
font-weight: 400;
font-size: 14px;
line-height: 20px;
letter-spacing: 0px;

}
</style>
