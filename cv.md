# Kristina Naydenova
![photo](/pic.jpg)
## Contacts
**Tel.** +48 574 166 151  
**e-mail** kristina.shpakovskaya@gmail.com  
**Telegram** @kristinanaydenova  
[Behance](https://www.behance.net/e09138a5)

## About
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin non enim et lectus faucibus ullamcorper. Maecenas interdum pellentesque scelerisque. In sed nunc interdum, vestibulum augue sit amet, aliquam felis. Curabitur porta massa in venenatis malesuada. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Curabitur efficitur elit malesuada hendrerit elementum. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nunc accumsan lorem ac lorem sodales tempus. Nulla urna dolor, luctus id rhoncus vel, euismod ac nibh.

## Skills
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin non enim et lectus faucibus ullamcorper. Maecenas interdum pellentesque scelerisque. In sed nunc interdum, vestibulum augue sit amet, aliquam felis. Curabitur porta massa in venenatis malesuada.  
## Experience
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin non enim et lectus faucibus ullamcorper. Maecenas interdum pellentesque scelerisque. In sed nunc interdum, vestibulum augue sit amet, aliquam felis. Curabitur porta massa in venenatis malesuada. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Curabitur efficitur elit malesuada hendrerit elementum. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nunc accumsan lorem ac lorem sodales tempus. Nulla urna dolor, luctus id rhoncus vel, euismod ac nibh. 
## Code example
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
## Courses
2022: UI/UX design IT Academia

## Languages
- English B2
- Russian native
- Polish A2
