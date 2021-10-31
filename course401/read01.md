# Node Ecosystem, TDD, CI/CD

### Describe (in plain English) what Array.map() does

- it loop throw the arrays' elements and make a new array with some configuration of the the original array elements
  > arr.map((element,index,arr)=>{ return element \* 2 })

### Describe (in plain English) what Array.reduce() does

- it executes a reducer function for each value of an array, and it returns one value which is the accumulated result.
  > arr.reduce((previousValue, currentValue)=>{ return previousValue + currentValue }, initialValue)

### Provide code snippets showing how to use superagent() to fetch data from a URL and log the result With normal Promise .then() syntax.

    let  characters = [] ;
    superagent.get('https://swapi.dev/api/people/1')
    .then(result=>{
      characters = result.body;
      let c = characters.name;
      console.log({'Luke Skywalker':characters.url})
    })
    .catch(err=> console.log(err));

### Again with async / await syntax

    async function getCity (cityName){
       let results = await superagent.get(`https://geocode.xyz/${cityName}?json=1`);
        console.log(cityName);
      console.log('longitude:',results.body.longt);
      console.log('latitude:',results.body.latt);
    }

### Explain promises as though you were mentoring a Code 301 level student

- it say to the javascript do your work, I don’t care how long it takes and I’m going to go ahead and keep working … but let me know when you’re done .then() give me the data and let me deal with it myself”

### Are all callback functions considered to be Asynchronous? Why or Why Not?

- No, the callback functions are not Asynchronous; id you need to make it as so, you have to but use promises or async method. otherwise, the callBack will take order by priority.
