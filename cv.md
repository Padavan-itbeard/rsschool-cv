# [rsschol-cv](https://github.com/Padavan-itbeard/rsschool-cv/cv)

# Alexander Ivanov
# My Contact Info:
- Phone: +8 912 766 47 01
- E-mail: [alexandr.ivanov.1024@gmail.com](alexandr.ivanov.1024@gmail.com)
- GitHub: [Padavan-itbeard](https://github.com/Padavan-itbeard)
# About Me
# Code Example
[Ninja vs Samurai: Attack + Block](https://www.codewars.com/kata/517b2bcf8557c200b8000015)
```
Position = {
  high: 'h',
  low: 'l'
}

Warrior = function(name){
  this.name = name;  
  this.health = 100;
}

Warrior.prototype = {
  attack: function(enemy, position){
    if (enemy.block != position){
      var damage = position === Position.high ? 10 : 5;
      // if enemy is not blocking at all then give more damage
      if (!enemy.block){
        damage += 5;
      }
      setHealth.call(enemy, enemy.health - damage);   
    }
  }
}

// private functions
function setHealth(value){
  this.health = Math.max(0, value);
  if (this.health == 0){
    this.deceased = true;
    this.zombie = false;
  }
  else if(this.deceased){
    this.zombie = true;
  }
}
```
# Experience
## Current Position
**Company:** OOO "Techno Diasoft"  
**Role:** Lead Expert Programmer  
**Project:** Acquiring Personal Account  
**Client:** PJSC Sberbank  

**Key Responsibilities:**  
- Developing the front-end part of the project.  
- Conducting code reviews.  

**Technology Stack:** React.js, Redux, SWR, Webpack, Less.  
## Previous Experience**  

**Company:** OOO StandardProekt  
**Role:** Senior Software Developer  
**Project:** Development of a Single Page Application (SPA) for the system that tracks and processes court decisions.  
**Client:** Moscow Automobile and Road Construction State Technical University (MADI).  

**Project Overview:**  
The application is a journal system designed for inspectors to record and process court decisions efficiently.  

**Key Responsibilities:**  
- Front-end application development.  
- Participating in task estimation and planning.  
- Conducting code reviews.  

**Achievements:**  
- Modernized the application to meet current React standards.  
- Optimized the search functionality and eliminated system freezes.  

**Technology Stack:** React.js, Redux, Redux-Form, React-Router, Immutable.js, PrimeReact, Sass, Assembly, Lodash, TinyMCE.  

---

**Company:** WEBRISE  
**Role:** Full Stack Developer  
**Project:** Development of a SPA for cryptocurrency exchange management.  

**Project Overview:**  
A multi-trading platform enabling operations across seven major cryptocurrency exchanges, including automation capabilities for trading.  

**Achievements:**  
- Overcame significant development delays, bringing the project back on schedule.  
- Standardized platform functionality to match the best exchange's performance.  
- Enhanced and tested the automated trading system.  

**Key Responsibilities:**  
- Developing the front-end and back-end of the application.  
- Database administration.  
- Implementing CI/CD pipelines.  
- Conducting code reviews.  

**Technology Stack:** React, Redux, Thunk, SCSS, WebPack, Node.js, Express, NGinx, PostgreSQL.  





