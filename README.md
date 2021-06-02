# Python-Remove-Watermark
A program to remove the watermark from a PDF file. 

### Usages
```shell
usage: python3 main.py -i <input.pdf> -o <output.pdf>
```

### How?

1. convert the PDF file into images using `pdf2image`
2. convert the images to numpy array
3. find the specific pixel by watermarks' rgb values and change them into (255,255,255)
4. save the modified images


### environment
`pdf2image`: pip install pdf2image

`poppler`: brew install poppler


### results
![image](./result.png)
