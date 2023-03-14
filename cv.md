## KRISTINA NAYDENOVA

![Текст с описанием картинки](/images/picture.jpg)

# Contacts

**Tel.** +48 574 166 151  
**e-mail** kristina.kristina@gmail.com  
**Discord** KristinaN#6531
[Behance](https://www.behance.net/e09138a5)



# About


# Skills
HTML  
CSS  
JavaScript  
React  
Git  
UI/UX Design  
Photoshop  

# Experience
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
# Languages
