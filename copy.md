.menu__checkbox {
	position: absolute;
	left: -9999px;
}

.menu__list {
	margin: 0;
	padding: 0;
	list-style: none;
	display: none;
  text-align: center;
}

.menu__link {
	display: block;
	padding: 15px;
	text-decoration: none;
	color: black;
}

.menu__link:hover {
  color: blueviolet;
}

.menu__checkbox:checked ~ .menu__list {
	display: block;
}

.logo {
  color: black;
}

.header__container {
  display: flex;
  margin: 20px;
  justify-content: space-between;
  align-items: center;
}