# Extended Smartdoc Dataset

This repository introduces the dataset named Extended Smartdoc Dataset.

The Extended Smartdoc Dataset was proposed in the article "HU-PageScan: a fully convolutional neural network for document page crop".
![Cick here](https://digital-library.theiet.org/content/journals/10.1049/iet-ipr.2020.0532) to go to the article.

The Extended Smartdoc Dataset is composed of the document's imagens presents at Smartdoc Dataset (http://www.cvc.uab.es/~marcal/pdfs/ICDAR15e.pdf) (that is: datasheet, letter, magazine, paper, patent, and tax). These documents were inserted over different backgrounds acquired from various smartphone's cameras with different colors, textures, lighting conditions and different resolutions. These backgrounds are the amount of 213 and represent several possible situations of real-world. Also, each document image was blended with some image background with a random rotation.

To build the image's dataset, we divided the background's image in  75\% for training and 25\% for validation. So, the validation dataset not uses the same backgrounds used at the training dataset. Figure bellow shows an example of the images build for Extended Smartdoc Dataset.

## Example of picture

![Extended Smartdoc Dataset](https://raw.githubusercontent.com/ricardobnjunior/Extended-Smartdoc-Dataset/master/images/SmartdocDataset2.png?token=AENMRWXHEHEAQW43R5MIK6K5WGUXQ)


### Download 

The Extended Smartdoc Dataset is a very large dataset, that's why we peovide the sample dataset, that is smaller, and you can download the Sample Dataset to verify if you wish to use the dataset in your research.

Sample dataset: https://drive.google.com/file/d/1RhfZsyZL-x3Z70kgXOarVWvaiVpxeXFi/view?usp=sharing

Full dataset: https://drive.google.com/drive/folders/1G3xbBFrkNKKKnqlkGvDA4quG19rUmCnZ?usp=sharing

### Citation

Use this BibTeX  to cite this repository:

```
@ARTICLE{
   author = {Ricardo Batista das Neves Junior},
   author = {Estanislau Lima},
   author = {Byron L.D. Bezerra},
   author = {Cleber Zanchettin},
   author = {Alejandro H. Toselli},
   ISSN = {1751-9659},
   language = {English},
   title = {HU-PageScan: a fully convolutional neural network for document page crop},
   journal = {IET Image Processing},
   year = {2020},
   month = {December},
   publisher ={Institution of Engineering and Technology},
   copyright = {© The Institution of Engineering and Technology},
   url = {https://digital-library.theiet.org/content/journals/10.1049/iet-ipr.2020.0532}
}
```