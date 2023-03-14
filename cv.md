## KRISTINA NAYDENOVA

![Текст с описанием картинки](/pic.jpg)

# Contacts

**Tel.** +48 574 166 151  
**e-mail** kristina.shpakovskaya@gmail.com  
**Discord** KristinaN#6531  
[Behance](https://www.behance.net/e09138a5)



# About
I am an enthusiastic person currently pursuing a career in Front End Development. Have a passion for learning and constantly strive to expand my knowledge and skill set. I am a fast learner who is not afraid to tackle difficult challenges.

Dedicated to personal and professional growth, and I am committed to making a positive impact on both the company and society as a whole. 
Overall, I am excited to bring my skills and enthusiasm to a company where I can continue to learn and grow, while making a meaningful contribution to the team and society.


# Skills
- HTML  
- CSS  
- JavaScript  
- React  
- Git  
- Figma  
- Photoshop  

# Experience
2020 - now UI/UX designer and front-end developer (e-commerce website with CRM and accounting system)

# Code example

```
function l3MainSliderBtnClick(e){
    let gap = 0;
    let itemWidth = bigPics[0].clientWidth;
    let totalItemsNum = bigPics.length;
    let itemsHiddenLeftNum = Math.round((sliderContainer.scrollLeft+gap)/(itemWidth+gap));
    let showCapacityNum = Math.round((sliderContainer.clientWidth+gap) / (itemWidth+gap));

    let num = 0;

    if (e.currentTarget.classList.contains('btn-left')) {
        num = itemsHiddenLeftNum - showCapacityNum;
        if (num < 0) num = 0;
    }
    else {
        num = itemsHiddenLeftNum + showCapacityNum*1;//one, because index is less for 1
        if ((num > totalItemsNum-1)) num = totalItemsNum-1;
    }
    bigPics[num].scrollIntoView({ behavior: 'smooth', block: 'nearest'})
}
```

# Courses
2022: UX/UI-design IT-Academy

# Languages
English: B2  
Russian: native  
Polish: A2  
Belarusian: B2  
Ukrainian: B2
