
# Natalia Rudenko

![Руденко Наталья](img/natali.jpg "Фото")

## Contacts

**Phone:** 89292696969

**Email:** melvia.nr@gmail.com

**Location:** Tyumen, Russia

**Discord:** natalyarudenko


## About me

I'm an avid front-end programmer who loves to combine visualization and code. For a long time I worked in support of programs, now I write them myself. I try to improve my level at least sometimes so as not to feel like a bad programmer. I dream of getting into web design. I try to check the functionality of the code as much as possible.


## Skills

Program Languages and technologies: Javascript, Java-Core, C#, 1C, SQL, CSS, HTML, Git, webpack, MS SQL, Typescript, Angular, NgXS, SCSS


## Code examples

**Typescpipt**

```
export const isPangram = (phrase: string): boolean => 
{
  const strABC: string  = 'abcdefghijklmnopqrstuvwxyz';
  const  phraseNew: string = [...new Set([...phrase.toLowerCase()])].sort().join('').replace(/[^a-z]/g, '');
  return (phraseNew ===  strABC);  
}
```

**JavaScript:**

```
function count(string) 
{
  let counterObj = {};
  counterObj = [...string].reduce((acc, letter) => 
  {
    if(acc.hasOwnProperty(letter))  {    
      acc[letter]=acc[letter]+1;
      return acc;            
    } else {
    acc[letter] = 1;
    return acc;      
    }
  }, counterObj);
  return counterObj;
}
```

## Work experience

Workplace             | Position 
:--------------------:|:-----------------------:
PJSC "ZAPSIBCOMBANK"  | Programmer
LLC "Technocom"       | Software engineer
LLC "Creative"        | Junior programmer


## Education

  *Surgut State University*, specialty - engineer of automated information processing and control systems.

### Courses

Place                                                | Name of Course 
:---------------------------------------------------:|:--------------------------------------------:
 Creative                                            | Web Developer using REACT JS 
 GAUDO "Regional Information and Educational Center" | JSC "Sbertech", Programming in Java 
 GAUDO "Regional Information and Educational Center" | Programming in Javascript and frameworks
 Tyumen-Soft LLC                                     | Introduction to configuration in the 
                                                     | 1C/: Enterprise 8 system.

## English

Proficiency level: A2. 

Translated several articles using the Angular framework, tried live communication at a conference with English-speaking speakers.
