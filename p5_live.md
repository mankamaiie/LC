// https://orangemilkrecords.bandcamp.com/track/hikari


let libs = ['https://unpkg.com/hydra-synth', 'includes/libs/hydra-synth.js']
let hydra = new Hydra()
hydra.setResolution(window.innerWidth*2, window.innerHeight*2) // retina res

// here lol

bpm = 120
voronoi(7,2,1)
  .scale(() => Math.sin(time)+1*2)
  .repeat(() => Math.sin(time)*10)
.modulate(noise(6),.22)
//.diff(o0)
.modulate(noise())
.add(gradient(1,1))
//.thresh()
.colorama([1,2])
	.rotate(1,1)
//.modulatePixelate(noise(25,0.5),100)
//.diff(o0)
.modulateScale(osc(3,0.5),-0.5)
.mask(shape(([3,5]))
.scale(3))
.repeat(40,40)
.kaleid([5,50])
//.luma(0.5,0.1)
.invert([0,1])
.scroll(0.1,-0.3)
.rotate()
.add(o0,0.5)


  .modulateRotate(o0)
  .scale(() => Math.sin(time)+1 *1.5)
  .modulate(noise(2,2))
  .rotate(1, .2)
  .modulate(noise(4))
  .add(gradient())



.add(solid(.2,0,.3)).mask(shape([20,5]).scale([1,2,3]).repeat(5,5)
.rotate(1.5)).scrollX([0.1,-0.0625,0.005,0.00001],0)

.out(o0)








// ends here

###We started by choosing a song: "Hikari" from "Ez Minzoku" by Foodman. 

###Next thing we did we call Hydra by:
///
let libs = ['https://unpkg.com/hydra-synth', 'includes/libs/hydra-synth.js']
let hydra = new Hydra()
hydra.setResolution(window.innerWidth*2, window.innerHeight*2) // retina res
///
###We initially set the speed, but then we adjusted it to match the song's bpm.

###We set Voronoi as our source and started experimenting with it by adding a bunch of things. 

###we used .scale, .repeat, .kaleid and others just to basically see what’s gonna happen. Lilith wanted to add some circle shape sho we did by mask.shape, Zoe wanted it to be purple - we did some nice purple to it as well - Zoe really knows how to get the right collor - that’s so cool! I really love the .modulatePixelate with noise - so we added that as well. 

###Overall, it was so fun to work with my friends Zoe and Lilith and see what happens by experimenting as much as we can. 

###we did art!!!