# BGA Reversi Tutorial
Board Game Arena (BGA) Studio is a platform to build online board game adaptations using the BGA platform. 

BGA strongly suggests going through one of their tutorials before starting a new game. This repo is my attempt at following along with their [Reversi Tutorial](https://studio.boardgamearena.com/doc/Tutorial_reversi)


## Right Now
I am following the aforementioned tutorial and I'm at this point:
> Note that we are using a jpg file. Jpg are lighter than png, so faster to load. Later we are going to use PNGs for discs for transparency purpose.
> 
> Now, let's make it appear in our game:
> 
> upload board.jpg in your `img/` directory. Warning: use lowercase file names!
> 
> edit `reversi_reversi.tpl` to add a `div` for your board.
>
> Note: If you are building this game by following the tutorial, you will have a different project name than `reversi` (i.e. `mygame_mygame.tpl`). The file names in your project will be different than shown in this tutorial, replacing `reversi` with your project name. It should be trivial to find the right file in your project, but be sure that any code (other than comments) that references `reversi` is changed to your actual project name.
> 
>     <div id="board">
>      </div>
> edit your `reversi.css` file to transform it into a visible board:
> 
>     #board {
>        width: 536px;
>        height: 528px;
>        background-image: url('img/board.jpg');
>     }
> 
> Important: refresh your page. Here's your board: 

I've added the div here: https://github.com/VickiLanger/BGA-Reversi_Tutorial/blob/3b57546d31e94de24e1cf80ea83dc7c349aefc6b/tutorialreversicheesepuppy_tutorialreversicheesepuppy.tpl#L29

and the css here: https://github.com/VickiLanger/BGA-Reversi_Tutorial/blob/3b57546d31e94de24e1cf80ea83dc7c349aefc6b/tutorialreversicheesepuppy.css#L51
