<script setup>

</script>

<template>
	<div class="container">
		<div class="container__inner">
			<div class="header-top">
				<div class="header-top__menu">
					<div class="header-top__menu-content">
						<img src="/public/svg/Icon 28 - 24px.svg">
						<span>Москва</span>
					</div>
					<div class="header-top__menu-content">
						<img src="/public/svg/Shipping 4 - 24px.svg">
						Доставка и оплата
					</div>
					<div class="header-top__menu-content">
						<img src="/public/svg/Icon 35 - 24px.svg">
						Адрес и часы работы
					</div>
				</div>
				<div class="header-top__callback">
					<div class="header-top__callback-content">
						<img src="/public/svg/Communication 1 - 24px.svg">
						<span>market@estatut.ru</span>
					</div>
					<div class="header-top__callback-content">
						<img src="/public/svg/Device 32 - 24px.svg">
						<span>8 (968) 660-65-50</span>
					</div>
					<div class="header-top__callback-content">
						<img src="/public/svg/Icon 28 - 24px.svg">
					</div>
				</div>
			</div>

			<div class="header-main">
				<div class="header-main__content">
					<div class="header-main-content___search">
						<img
							src="/public/Новая папка/logo.png"
							alt="Logo"
						>
						<div class="header-main-content__input">
							<input
								class="header-main-content__input-content"
								type="text"
								placeholder="Автор, название, ISBN"
							>
							<button class="header-main__content-button">
								<img src="/public/svg/Interface 52 - 24px.png">Искать
							</button>
						</div>
					</div>

					<div class="header-main__cart">
						<div class="header-main__cart-content">
							<img src="/public/svg/Interface 100 - 24px.svg">
							<span>Отложено</span>
						</div>
						<div class="header-main__cart-content">
							<img src="/public/svg/Interface 166 - 24px.svg">
							<span>Войти</span>
						</div>
						<div class="header-main__cart-content">
							<img src="/public/svg/Icon 1 - 24px.svg">
							<span>Корзина</span>
						</div>
					</div>
				</div>
				<nav class="header-main__nav">
					<div class="header-main__nav-content">
						<img src="/public/Новая папка/Interface 85 - 24px.png">Каталог
					</div>
					<div class="header-main__nav-content">
						Авторы
					</div>
					<div class="header-main__nav-content">
						Новинки
					</div>
					<div class="header-main__nav-content">
						<img src="/public/Новая папка/Icon 16 - 24px.png">Скидки
					</div>
					<div class="header-main__nav-content">
						Партнёрам
					</div>
					<div class="header-main__nav-content">
						Мы
					</div>
				</nav>
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
.header-top{
	font-size: 14px;
	height: 50px;
    display: flex;
    justify-content: space-between;
	border-bottom:1px solid gray;
}
.header-top__menu
{
	display: flex;
	flex-wrap: nowrap;
	width: 40%;
	justify-content: space-between;
	align-items: center;

}
.header-top__menu-content{
	display: flex;
	justify-content: space-around;
	height: 20px;
}
.header-top__callback
{
	width: 30%;
	display: flex;
	flex-wrap: nowrap;
	justify-content: space-between;
	align-items: center;
}
.header-top__callback-content
{
	display: flex;
	height: 20px;
	justify-content: space-around;

}
.header-main{
	font-size: 14px;

}
.header-main__content{
	display: flex;
	height: 40px;
	margin-top: 21px;
}
.header-main-content___search{
	width: 60%;
	height: 40px;
	display: flex;
}
.header-main-content__input{
	width: 80%;
	display: flex;
	justify-content: flex-start;
	margin-left: 30px;
	width: 576px;
}
.header-main-content__input-content{
	width: 450px;
	border:1px solid #DFE0E1;
	padding-left: 16px;
}
.header-main__content-button{
	background-color: #FF7A00;
	width: 123px;
	display: flex;
	align-items: center;
	justify-content: center;
	color: white;
	padding: 8px;
}

.header-main__cart{
display: flex;
width: 75%;
justify-content: flex-end;
align-items: center;

}
.header-main__cart-content{
	display: flex;
	height: 20px;
	justify-content: space-between;
}
.header-main__cart-content:not(:last-child){
	margin-right: 30px;

}
.header-main__nav{
	margin-top: 20px;
	margin-bottom: 20px;
	display: flex;
	width: 484px;
	height: 20px;
	justify-content: space-between;
	align-items: center;
}
.header-main__nav-content{
	display: flex;
}
.header-main__nav-content:nth-child(4){
	color: red;
}
</style>
