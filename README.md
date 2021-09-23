<h1 align="center">Samuel Risbond Lugona</h1>

<h2 align="center">A little About me</h2>

```ts
import SoftwareDeveloper, { MyBiography } from 'risbond';

export default class Bio extends SoftwareDeveloper {
  name     = 'Samuel Risbond Lugona';
  title    = 'Software Developer';
  company  = 'Luris Systems';
  location = 'Kampala, Uganda';
  
  getDetails(): MyBiography {
    return {
      "- ⚡ Quick bio:":                    "Quality oriented self motivating developer that is commercially-ware, evolving and enthusiastic about creating things",
      "- 🔭 I’m currently working at":      `${this.company} as ${this.title}`,
      "- 👯 I’m looking to collaborate on": "Node, React, PHP, Python and any other Javascript related projects",
      "- 💬 Ask me about":                  "Node, React, PHP, SQL, CSS, Software Design & Architecture, Web-Development and any thing Photoshop related",
      "- 📫 Reach me at:":              "samrisbond@gmail.com",
    };
  }
}
```
