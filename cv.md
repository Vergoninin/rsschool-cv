# Pavel Khareuka

## Contacts:
  * Location: Minsk, Belarus
  * Email: paul.horevko@gmail.com
  * GitHub: [vergoninin](https://github.com/Vergoninin)
  * Discord: Vergoninin

## Skills:
  * HTML
  * CSS
  * JavaScript(Basic)
  * Git, GitHub

  ## Code Examples:
```JavaScript
function binary_search(sorted_List, item) {
  let lowIndex = 0;
  let highIndex = sorted_List.length - 1;
  let midIndex = 0;
  let guess = 0;

  while (lowIndex <= highIndex) {
    midIndex = (lowIndex + highIndex)/2;
    guess = sorted_List[midIndex];

    if (guess == item) return midIndex;
    if (guess > item) {
      highIndex = midIndex - 1;
      } else {
        lowIndex = midIndex + 1;
      }
  }
  return -1;
}

list = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15];

binary_search(list, 9);
```