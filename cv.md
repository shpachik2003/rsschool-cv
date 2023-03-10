#KRISTINA NAYDENOVA

##Contacts
##About
##Skills
##Experience
##Code example
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
##Courses
##Languages