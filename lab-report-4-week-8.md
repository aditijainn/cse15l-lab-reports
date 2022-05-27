# **Writing Clean Code**

## Links
1. [My markdown-parse repository](https://github.com/aditijainn/markdown-parser.git)
2. [The repository we reviewed](https://github.com/aejiang/markdown-parser)

## Snippet 1
1. Expected output using VScode preview:
![Image](labreport4pics/lab4.1.png)
2. Junit test I created for it:
![Image](labreport4pics/lab4.2.png)
3. Corresponding output when running the test:
    - My implementation: 
    ![Image](labreport4pics/lab4.3.png)
    - The implementation I reviewed in Week 7:
    ![Image](labreport4pics/lab4.4.png)
4. Small code change: To check if the code inside the backticks changes the markdown link. This is because backticks can make it so that the code within `[]` or `()` would not generate a link, making the markdown link not work.

## Snippet 2
1. Expected output using VScode preview:
![Image](labreport4pics/lab4.5.png)
2. Junit test I created for it:
![Image](labreport4pics/lab4.6.png)
3. Corresponding output when running the test:
    - My implementation: 
    ![Image](labreport4pics/lab4.7.png)
    - The implementation I reviewed in Week 7:
    ![Image](labreport4pics/lab4.8.png)
4. Small code change: Check if each type of bracket (parentheses, escaped bracket, bracket) has closing pair within the link's formatted brackets as if they are closed they won't affect the markdown links.

## Snippet 3
1. Expected output using VScode preview:
![Image](labreport4pics/lab4.9.png)
2. Junit test I created for it:
![Image](labreport4pics/lab4.10.png)
3. Corresponding output when running the test:
    - My implementation:
    ![Image](labreport4pics/lab4.11.png)
    - The implementation I reviewed in Week 7:
    ![Image](labreport4pics/lab4.12.png)
4. Small code change: Check if there are newlines contained with the parentheses / brackets because links only work when all needed parts of the link are next to each other regardless of seperate lines, for example it works when ends of the brackets / parentheses aren't seperated by newlines as this is a needed part of the link formatting. 
