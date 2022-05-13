# visualizing-2D-image-slices-from-pytorch-tensor-3D-image-
This notebook contains simple python implementation to be used to visualize 2D slices from a 3D tennsor image in pytorch tensor format *.pt 

we can visualize 20 slices in axial, coronal or sagittal plane

pass in the 3D tensor image location, start slice and end slice number and plane direction in the function

select plane = 'a', 'c', or 's' . 
'a' stands for axial plane
'c' stands for coronal plane
's' stands for sagittal plane

and now we get 20 images of within the slice range.

currently the function can handle 20 images, so the different between start and end slice must be 20 or less than 20. 

There is a plan to update the code to support any number of slices.
