# Slide-Library
 Para iniciar o slide
 
 
#### Slide.init inicia o slide
slide.init();

####  Slide addAroow coloca botoes de next and prev. Basta apenas colocar as classes 
slide.addArrow('.prev', '.next');

#### Slide addControl coloca a paginação de acordo com a imaguem , Basta apenas criar uma ul e colocar a classe
slide.addControl('.custom-controls');


Exemplo: 

>import SlideNav from './slide.js';

>const slide = new SlideNav('.slide', '.slide-wrapper');

>slide.init();

>slide.addArrow('.prev', '.next');

>slide.addControl('.custom-controls');
