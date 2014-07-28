# Expérimentations avec WebGL

Ce repo contient une partie de mes essais avec WebGL (version d'OpenGL basée sur OpenGL ES qui est elle-même basée sur OpenGL).

- **Mandelbrot** : La fractale de Mandelbrot implémentée dans un fragment shader.

- **Wall of waves** : Des sortes de vagues créées à partir d'une grille, l'animation est faite dans le vertex shader à coup de trigonométrie. [Demo](http://mraaaah.fr/WebGL/wall_of_waves.html)

- **Torus** : Un tore sur lequel est appliqué un ombrage de phong via le fragment shader. [Demo](http://mraaaah.fr/WebGL/torus.html)

# Divers

La structure de base de mes animations est tirée de [Learing WebGL](http://learningwebgl.com/blog/?page_id=1217). Le code peut contenir des bugs, j'apprends à manier les VBO et les shaders via ces animations.

À l'heure ou j'écris ces lignes Safari ne supporte pas WebGL (que ça soit la version desktop ou iOS) et il me semble que Chrome désactive l'antialiasing sous Os X (du moins sur mon vieux MacBook).

