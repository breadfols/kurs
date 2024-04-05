<script>
	// @ts-nocheck

	import CarCard from '../Cars/CarCard.svelte';
	import Diler from '../Dilers/DCDiler.svelte';
</script>

<div class="films">
	<div class="container mx-auto">
		<h1 class="text_img">Работаем более<br /> чем с 1000 дилерами<br /> по всей России</h1>
	</div>
	<div class="container mx-auto">
		<img class="car" src="car_main.png" alt="" />
	</div>
	<div class="container mx-auto">
		<div class="text">
			<h1>Найди свой идеальный автомобиль</h1>
			<td width="10%">
				<h2 class="mark"><button>Acura</button></h2>
				<h2 class="mark"><button>Audi</button></h2>
				<h2 class="mark"><button>Bently</button></h2>
				<h2 class="mark"><button>BMW</button></h2>
				<h2 class="mark"><button>Bugatti</button></h2>
			</td>
			<td width="10%">
				<h2 class="mark"><button>Cadillac</button></h2>
				<h2 class="mark"><button>Cherry</button></h2>
				<h2 class="mark"><button>Chevrolet</button></h2>
				<h2 class="mark"><button>Citroen</button></h2>
				<h2 class="mark"><button>Dodge</button></h2>
			</td>
			<td width="10%">
				<h2 class="mark"><button>Ferrari</button></h2>
				<h2 class="mark"><button>Ford</button></h2>
				<h2 class="mark"><button>Hawal</button></h2>
				<h2 class="mark"><button>Honda</button></h2>
				<h2 class="mark"><button>Показать всё</button></h2>
			</td>
		</div>
	</div>
	<div class="container mx-auto">
		<h1 class="text">Лучшая цена</h1>
		<div class="car_grid">
			<CarCard />
			<CarCard />
			<CarCard />
			<CarCard />
			<CarCard />
			<CarCard />
			<CarCard />
			<CarCard />
		</div>
	</div>
	<div class="container mx-auto">
		<h1 class="text">Посетите наший дилеров</h1>
		<div class="diler_grid">
			<Diler />
			<Diler />
			<Diler />
			<Diler />
			<Diler />
			<Diler />
		</div>
	</div>
	<div class="container mx-auto">
		<h1 class="text">Почему вы должны покупать у нас</h1>
		<div class="flex gap-5 justify-between">
			<div class="why">
				<div class="txt">
					<img class="mb-2 mx-3" src="/icon/star.png" alt="">
				<h2><p class="mb-2"><b>Награды</b></p>
				Наш сайт неоднократно оценивалась лучшим сайтом по подбору автомобилей</h2>
				</div>
			</div>
			<div class="why">
				<div class="txt">
					<img class="mb-2 mx-3" src="/icon/track.png" alt="">
				<h2><p class="mb-2"><b>Доставка</b></p>
				доставим вам ваш автомобиль прямо до дома, в удобное для вас время</h2>
				</div>
			</div>
			<div class="why">
				<div class="txt">
					<img class="mb-2 mx-3" src="/icon/shield.png" alt="">
				<h2><p class="mb-2"><b>Возврат</b></p>
				в случае если вам автомобиль не понравился или он вам не подходит, вы можете вернуть в течение 2 недель его нам</h2>
				</div>
			</div>
			<div class="why">
				<div class="txt">
					<img class="mb-2 mx-3" src="/icon/fist.png" alt="">
				<h2><p class="mb-2"><b>Страховка</b></p>
					подберем для вас самый выгодный способ страхования, чтобы вы ничего не переплачивали</h2>
				</div>
			</div>
		</div>
	</div>
</div>

<style lang="scss">
	.films {
		background: grey;
		color: white;
		padding: 50px 0;
		border-top: 1px solid var(--light);
		height: 100%;
	}
	.car {
		width: 100%;
		margin-left: auto;
		margin-right: auto;
		margin-top: -10px;
		margin-bottom: 20px;
	}
	.text_img {
		margin-left: 100px;
		margin-top: 200px;
		position: absolute;
	}
	.mark {
		margin-bottom: 10px;
	}
	.text {
		color: black;
		margin-left: 30px;
	}
	.car_grid {
		display: grid;
		grid-template-columns: repeat(4, 1fr);
		gap: 40px;
	}
	.diler_grid {
		display: grid;
		grid-template-columns: repeat(3, 1fr);
		gap: 30px;
	}
	.why {
		width: 300px;
		height: 400px;
		background-color: white;
		border-radius: 30px;
		color: black;
	}
	.txt {
		margin-left: 20px;
		margin-top: 20px;
	}
</style>
