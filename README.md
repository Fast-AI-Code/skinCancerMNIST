## Skin Cancer MNIST: HAM10000

## Networks (Results)

- resnet34 pretrained + adamW+ wd = 1e-3+ oversampling
    - overfitting like hell initially
- resnet34 pretrained + adamW+ wd = 1e-3+no oversampling
    - overfitting like hell initially too but more than oversampled
- resnet50 pretrained + adamW+ wd = 1e-3+no oversampling
    - even more overfitting
- resnet34 not pretrained + adamW+ wd = 1e-3+ oversampling
    - less overfitting
    - still over fit
- resnet34 not pretrained + adamW+ wd = 1e-1+ oversampling+ mixup
    - no overfitting
    - doesnt do that great tho 
- resnet34 pretrained + adamW+ wd = 1e-1+ oversampling+ mixup
    - no overfitting
    - 71%
- vgg16bn pretrained + adamW+ wd = 1e-1+ oversampling+ mixup
    - no overfitting
    - 85.5%
- vgg19bn pretrained + adamW+ wd = 1e-1+ oversampling+ mixup
    - no overfitting
    - 88%

   


    

## Conclusion
- oversampling helps a lot
