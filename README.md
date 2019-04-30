### Creative developer cv

```js
export default class JsDeveloper {
  constructor() {
    this.hiringCompany = {};
  }

  static openProfile() {
    window.open("https://www.linkedin.com/in/max-marinich");
  }

  isOfferAwesome() {
    const { offer } = this.hiringCompany;
    // TODO add more checkers if an offer is competitive
    return Boolean(offer);
  }

  getDeveloper() {
    console.log(`Glad to be a part of ${this.hiringCompany.name} team`);
    JsDeveloper.openProfile();
  }

  joinTeam(hiringCompany) {
    this.hiringCompany = hiringCompany || {};
    this.isOfferAwesome() && this.getDeveloper();
  }
}

JsDeveloper.defaultSkills = {
  jsFormats: ["ES6", "TypeScript"],
  stylesPreprocessors: ["Sass", "Less", "Stylus"],
  viewFrameworks: ["React", "Angular", "JQuery"],
  mobileFrameworks: ["React Native"],
  performanceOptimization: ["SSR", "PWA"],
  testFrameworks: ["Chai", "Mocha", "Jest"],
  buildTools: ["Webpack", "Gulp"],
  packageManagers: ["npm", "yarn"],
  dashboardSystems: ["Jira", "GitHub"],
  DBMS: ["MongoDB", "MySQL", "Redis"],
  PMM: ["Scrum", "Less"],
  VCS: "Git"
};

JsDeveloper.thingsWantToDevelop = {
  vanillaJs: true,
  reactNative: true,
  nodeJs: true,
  viewLibrary: "React"
};

JsDeveloper.takeInterestIn = {
  gameDev: true,
  vueJs: true,
  AWS: true
};
```
