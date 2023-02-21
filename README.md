# Learning Markdown

Markdown has 6 level of headings. Corresponding to HTML tags h1,h2,...,h6.
Use hash(#) for heading.

# H1
## H2
### H3
#### H4
##### H5
###### H6
####### H7 This is not heading. Follow this guide carefully to learn markdown.

To make unordered list in MD, use single * or use single -. I will use single - because it looks cleaner and not get confused with other formatting options that use *.


Styling in markdown - 
- **bold** (double * for bold)
- *italics* (single * for italics)
- ~~strikethrough~~ (double tilde(~) for strike)

**Table of content**

(Use 1 for all the numbers so that when rearranging them, you don't have to do lot of work. MD will automatically do the work.)

1. Learn C++
1. Learn C programming 
1. Learn Bash Scripting
1. Learn Linux Fundamentals


## Learn C++

First learn how to install compiler for C/C++ : `sudo pacman -S gcc`

## Learn C programming  

Hello world program in C -
```c
#include<stdio.h>

int main(){
    printf("Hello World!!");

    return 0;
}
```

---

To add horizontal line use three dashes(-). Many platforms under h1 tag automatically adds a horizontal line.

---

To add block quotes use greater than symbol (>).

> Work hard in silence, let success make noise.
>
> -- <cite> Nikhil Sinha </cite>

There is no perfect way for block quotes. Its your choice. 

> Some people will love you, some will hurt you. Don't be sad for anything because Krsna is controlling everything. <br> <br>
> --  *Nikhil Sinha*


Nesting block quotes - 

> Brahama said to Narad that -
>
> By studing all the vedas, I have come to this conclusion that in the Kaliyug, only this mantra will help a soul. 
>
>> Hare krsna, hare krsna, krsna krsna, hare hare.
>>
>> Hare rama, hare rama, rama rama, hare hare.

To create a link - 

[Learn C programming](#learn-c-programming)

[Visit my website](https://nsinha.me)