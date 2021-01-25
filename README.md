## Fractal compression

Fractal compression is the algorithm of lossy compression that uses properties of contraction mappings and fancy math behind it in order to replace image data (for example, pixel representation of a data) by a huge function, which can generate image on which it was 'learned' from any other image, thanks to math and convergence properties.

See more about Fractal compression [here](https://en.wikipedia.org/wiki/Fractal_compression).

| Image | Iteration |
|:--------------|:----------|
|![Original image](test_files/baboon.png)|None (original image) |
|![Baboon_1](images/baboon_iteration_1.png) | 1 |
|![Baboon_2](images/baboon_iteration_2.png) | 3 |
|![Baboon_3](images/baboon_iteration_3.png) | 2 |
|![Baboon_4](images/baboon_iteration_4.png) | 4 |
|![Baboon_20](images/baboon_iteration_20.png) | 20 |

The function that generated all these images has a size of 16310, which is 44.1 smaller than the original image size.
