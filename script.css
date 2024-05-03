const clock = document.querySelector(".clock");
const dayname = document.querySelector(".day");

setInterval(() =>{
  let date = new Date();
  let hrs = date.getHours();
  let mins = date.getMinutes();
  let secs = date.getSeconds();
  let ampm = hrs >= 12 ? "PM" : "AM";
  let day = date.getDay();
  const days = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
  let myarr = date.toDateString().split(" ");
  
  hrs = hrs % 12;
  hrs = hrs ? hrs : 12;
  hrs = hrs < 10 ? "0" + hrs : hrs;
  mins = mins < 10 ? "0" + mins : mins;
  secs = secs < 10 ? "0" + secs : secs;
  
  clock.textContent = `${hrs} : ${mins} : ${secs} ${ampm} `;
  dayname.textContent = `${days[day]}, ${myarr[1]} ${myarr[2]}, ${myarr[3]}`;
  // console.log(myarr);

},1000)
