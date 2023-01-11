# draw_convnet

Python script for illustrating Convolutional Neural Network (ConvNet)

## Example image
With `flag_omit=False`
![](https://raw.githubusercontent.com/gwding/draw_convnet/master/convnet_fig.png)

With `flag_omit=True`
![](https://raw.githubusercontent.com/gwding/draw_convnet/ccaa14e2f8e41580bd29b97a501f7a4218779356/convnet_fig_with_omitted_channel.png)


## Known issues
The issue with matplotlib 2.0.x has been resolved, please let me know if you encounter problems.

~~`Line2D` doesn't seem to work well under `python3 + matplotlib 2.0.0` as pointed out by @ahoereth~~

## Using the code
It is NOT required to cite anything to use the code.

If you are not facing space limitation and it does not break the flow of the paper, you might consider adding something like "This figure is generated by adapting the code from https://github.com/gwding/draw_convnet" (maybe in the footnote).

FYI, originally I used the code to generate the convnet figure in this paper "Automatic moth detection from trap images for pest management".
