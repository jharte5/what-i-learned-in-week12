### What i learned in week 12

# CodeWars
    * Player Contact Manager
    * Welcome
    * The Office I Boredom Score

# Projects =>
* Object Stuff - learning about objects
  
    ``` javascript
     function setAge(person, age) {
    person.age = age
    }
     ```

* Thingagram - working with grid template areas

* An_Objectively_Challenging_Game - 
    ``` javascript
    const playerDmg = getAttackDamage(player.attackMin, player.attackMax);
    updatePlayerTxt(playerDmg);
    currentMonster.hitPoints -= playerDmg; 
    ``` 
* My Hosted Page - hosted a live page

* Just How We Roll - found the mean, median, and mode for die/dice
    ``` javascript
     function oneDieMean (sixes) {
    let total = 0, i;
    for (i = 0; i < sixes.length; i += 1) {
        total += sixes[i];
    }
    return total / sixes.length;

    }
     ```
* BS-Paint - took paint color from pallete to paintbrush to canvas 
    ``` javascript
    function switchFirstColor() {
    bigClass.replace(bigClass[1], 'color-1')
    }
     ```
* Transmogrify - pretense for follow up project

* All About that Text - made user input bigger x9000, counted it down, reversed it and title cased it ..
    ``` javascript
    const generateResult = (list) => {
    const result = document.querySelector(".result");
    result.innerText = `${list}`;
    }
     ```