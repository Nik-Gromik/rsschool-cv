
![foto for CV](https://user-images.githubusercontent.com/117682495/224129161-24498157-fe1f-4ad1-bd12-676f643c78df.jpg)
# **NIKOLAI GROMIK**
##       nikolay.gromik87@gmail.com      |      nikolay.gromik(@Nik-Gromik)   |      Brest, Belarus
____________________________________________________________________________________________________________________
## About me:
--------------------------------------------------------------------------------------------------------------------
  <p> I live with my wife and my daugther. We like traveling. Sometimes we ride a bicycle. I spend my free time with my family. </p>
  <p> I work as a builder. I like to implement innovative ideas from my clients. </p>
  <p> I want to change my job, I want to be a software developer. I think this  business field offers a lot of opportunities for professional development and career growth. I have  good communication skills. Also I’m hard-working and talented. Additionally I’m creative and self-motivated.  I’m a team player and ambitious.</p>
  
  ____________________________________________________________________________________________________________________
## Сode example: 
----------------------------------------------------------------------------------------------------------------------
function getTimeOfDay() {
    var hour = new Date().getHours();
    let x;
    if (hour <= 6) {
        x = "night";
    } else if (hour <= 12) {
        x = "Morning";
    } else if (hour <= 18) {
        x = "Afternoon ";
    } else {
        x = "Evening";
    }
    document.querySelector('.greeting').innerHTML = "Good " + x;
}


