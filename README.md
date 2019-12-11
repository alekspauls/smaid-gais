# smaid-gais
noliktava
 * http://revealjs.com

 * MIT licensed

 *

 * Copyright (C) 2019 Hakim El Hattab, http://hakim.se

 */

/*********************************************

 * GLOBAL STYLES

 *********************************************/

html {

  width: 100%;

  height: 100%;

  height: 100vh;

  height: calc( var(--vh, 1vh) * 100);

  overflow: hidden; }



body {

  height: 100%;

  overflow: hidden;

  position: relative;

  line-height: 1;

  margin: 0;

  background-color: #fff;

  color: #000; }



/*********************************************

 * VIEW FRAGMENTS

 *********************************************/

.reveal .slides section .fragment {

  opacity: 0;

  visibility: hidden;

  transition: all .2s ease; }

  .reveal .slides section .fragment.visible {

    opacity: 1;

    visibility: inherit; }



.reveal .slides section .fragment.grow {

  opacity: 1;

  visibility: inherit; }

  .reveal .slides section .fragment.grow.visible {

    -webkit-transform: scale(1.3);

            transform: scale(1.3); }



.reveal .slides section .fragment.shrink {

  opacity: 1;

  visibility: inherit; }

  .reveal .slides section .fragment.shrink.visible {

    -webkit-transform: scale(0.7);

            transform: scale(0.7); }



.reveal .slides section .fragment.zoom-in {

  -webkit-transform: scale(0.1);

          transform: scale(0.1); }

  .reveal .slides section .fragment.zoom-in.visible {

    -webkit-transform: none;

            transform: none; }

