as3-transitions-lib
===================

__Image Transitions Library for Actionscript 3__  (FP 9, FP10, FP11)


[![Live Example](/screenshots/screenshot1.png)](http://foo123.github.com/examples/as3-transitions-lib/)


###Live Example
* http://foo123.github.com/examples/as3-transitions-lib/

###Manual
* http://foo123.github.com/examples/as3-transitions-lib/manual.pdf

###How to Use
* register source (use symlink to com folder)
* register dependency folder

###Simple Sample Code
stage
|- mc1:MovieClip
|- mc2:MOvieClip

````
import com.nikos.mytransitions.*;
import fl.transitions.easing.*;

var foo:FadeTiles = new FadeTiles();
//FadeTiles.useFrames = false; //uncomment to use second for duration

addChild(foo);

foo.doit({
	toTarget:mc2,
	fromTarget:mc1,
	duration:40,
	easing:None.easeInOut,
	rows:8,
	columns:4,
	overlap:0.92,
	ordering:"random"
});
````

###TODO
* Transform the library into Flash IDE components ( _in progress_  incomplete source code has been added )

This project along with [flasher xml slideshow](https://github.com/foo123/flasher) were initiated some years back,
in order to create a generic slideshow framework based on flash for mostly work and demo purposes.

This project and (flasher) are still in progress, fully working nevertheless, but not developed anymore, the code is in a development state, with parts commented out here and there, as things were tested abd progressed.


*URL* [Nikos Web Development](http://nikos-web-development.netai.net/ "Nikos Web Development")  
*URL* [WorkingClassCode](http://workingclasscode.uphero.com/ "Working Class Code")  
