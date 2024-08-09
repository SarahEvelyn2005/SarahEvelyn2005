```js
import Desenvolvedor from "SarahEvelyn2005";

class SobreMim extends Desenvolvedor {
  nome = "Sarah Evelyn";
  area = "full stack";
  trabalho = "Level 33";
  local = "Brasília";
}

class Skills extends Desenvolvedor {
  linguagens = ["Java", "JavaScript", "TypeScript", "C#", "Python"];
  frameworks = ["React", "Angular"];
}

class Portfolio extends Desenvolvedor {
  constructor() {
    super();
    this.portfolioLink = "https://portifolio-psi-virid.vercel.app/";
  }

  render() {
    return `<a href="${this.portfolioLink}">Meu Portfólio</a>`;
  }
}

```
