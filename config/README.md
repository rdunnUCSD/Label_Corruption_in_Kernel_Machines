Different combinations of kernels and noise can be run by modifying the `script-params.json`. The modifiable tags are as follows:

`num_train` : int - The number of datapoints to use in the training dataset

`num_test` : int - The number of datapoints to use in the testing dataset

`min_noise` : float - The minimum value of noise to be applied to each kernel
  
`max_noise` : float - The maximum value of noise to be applied to each kernel
  
`noise_step` : float - The step size for iterating through `min_noise` to `max_noise`
  
`p_kernels` : list -> numeric - Each power of kernel that will be used
  
`c_modifiers` : list -> numeric - Each modifier of c that will be used (Value that modifies the denominator of the kernel function)
  
`num_classes` : integer - The number of classes to be used from the dataset (currently only works with 2 classes)
