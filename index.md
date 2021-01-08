>  Not everyone can become a great artist, but a great artist can come from anywhere.  
\- Anton Ego

# Table of contents
[About Me](/pictures/headshot.png)  

# About Me  
## Summary  
![My Headshot](/pictures/headshot.png)  
**Name:** Chad Makanaokeakua Wall  
**Age:** 20  
**Gender:** Male (He/Him)  
Just some random computer nerd who plays way too many games. Currently studying at UCSD for my bachelor's degree. Hobbies include digital art (though not very good), game design, and playing *way* too games (like I mentioned earlier). Currently in:  
* CSE101
* CSE 110
* CSE 151A
* PHIL 28  

## Favorites  
**Game:** Fallout: New Vegas  
**Movie:** Spirited Away  
**Book:** Catch-22  
![Personal Copy](/pictures/fav_book.jpg)  
(Personal copy I had since I was 13)  
**Show:** Venture Bros.  
**Band:** Gorillaz  
**Programming Language:** C#  
**Classes in UCSD (So far):**  
1. CSE 100
   - Professor Cao, Yingjun
2. CSE 130
   - Professor Polikarpova, Nadezhda
3. CSE 30
   - Professor Ord, Richard  

## Links  
[Piazza](https://piazza.com/careers/dashboard#/my_profile/jml95fggn794yz)  
[LinkedIn](https://www.linkedin.com/in/chad-wall-072131194/)  
Mysterious Song of the Week: www.youtube.com/watch?v=Yw6u6YkTgQ4  
[README.md](/README.md)  
# Cool Code  
Amazing Inverse Square Root Algorithm from Quake III:  
```
float Q_rsqrt( float number )
{
    long i;
    float x2, y;
    const float threehalfs = 1.5F;

    x2 = number * 0.5F;
    y  = number;
    i  = * (long * ) &y;
    i  = 0x5f3759df - ( i >> 1 );
    y  = * ( float * ) &i;
    y  = y * ( threehalfs - ( x2 * y * y ) );

    return y;
}
```  
[(Source & Explanation)](https://www.youtube.com/watch?v=p8u_k2LIZyo)  

# TODO
- [x] Pictures
- [x] Links
- [x] Headings
- [x] Styling text
- [x] Quoting text
- [x] Quoting code
- [ ] Section links
- [x] Relative links
- [x] Lists
- [x] Task lists
- [ ] ~~Take oveer the world~~