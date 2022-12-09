# **Nikita Pitalenko**
## **Junior Frontend Developer**

********* 

## **Contact information:**

* **Phone:** +48534341913
* **E-mail:** pitalenkopl@gmail.com
* **Telegram:** @nikita_pitalenko
* [Linkedin](https://www.linkedin.com/in/nikita-pitalenko-7759161b2/)
* [Github](https://github.com/walleq)

********* 

## **Briefly About Myself:** 

I have been working in the IT field for over 3 years. All this time I was engaged in recruiting. I also had experience learning JavaScript about 2 years ago and even got an internship. I work well in a team, I have good communication skills and excellent English.

***

## **Skills:**

* JavaScript Basics
* Git, GitHub
* VS Code, WEbstorm
* HTML, CSS

***

## **Code example:** 

I taked a part of my game **tic-tac-toe**.
```
  arr1.forEach((item, i) => {
    if (
      (winner[item[0]].firstChild && winner[item[0]].firstChild.classList.contains('plus')) &&
      (winner[item[1]].firstChild && winner[item[1]].firstChild.classList.contains('plus')) &&
      (winner[item[2]].firstChild && winner[item[2]].firstChild.classList.contains('plus'))
    ) {
      alert("Победил первый игрок");
      setFirstScore(firstScore + 1);
      score.innerText = `Счёт - ${firstScore}:${secondScore}`;
      clearFields();
    } else if (
      (winner[item[0]].firstChild && winner[item[0]].firstChild.classList.contains('minus')) &&
      (winner[item[1]].firstChild && winner[item[1]].firstChild.classList.contains('minus')) &&
      (winner[item[2]].firstChild && winner[item[2]].firstChild.classList.contains('minus'))
    ) {
      alert("Победил второй игрок");
      setSecondScore(secondScore + 1);
      score.innerText = `Счёт - ${firstScore}:${secondScore}`;
      clearFields();
    } else if (Array.from(winner).every(item => item.innerHTML)) {
      alert("Ничья!");
      clearFields();
    }
  });
}
```
***

## **Expirience:** 

***

## **Education:** 
**University:** Vitebsk State Technological University, Magistr, Engineer

***

## **English**
B2 (I got expirience speaking and working with englsih speaking costumers).