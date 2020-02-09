### Creative JavaScript Developer CV (Combo 💣🌶🔝👍😉)

```js
class JsDeveloper {
  constructor() {
    this.developer = {
      team: '',
    };
  }

  static openProfile() {
    window.open('https://www.linkedin.com/in/max-marinich');
  }

  static isOfferAwesome(offer) {
    // TODO add more checkers if an offer is competitive
    return Boolean(offer);
  }

  updateDeveloper({ team }) {
    this.developer.team = team;
  }

  getDeveloper() {
    const { team } = this.developer;

    console.log(`Glad to be a part of ${team} team`);
    JsDeveloper.openProfile();
  }

  joinTeam(hiringCompany) {
    const { offer, team } = hiringCompany || {};

    if (JsDeveloper.isOfferAwesome(offer)) {
      this.updateDeveloper({ team });
      this.getDeveloper();
    }
  }
}

JsDeveloper.defaultSkills = {
  jsFormats: ['ES6', 'TypeScript'],
  htmlPreprocessors: ['Jade', 'Pug', 'EJS'],
  cssPreprocessors: ['Sass', 'Less', 'Stylus'],
  viewFrameworks: ['React', 'Vue', 'Angular', 'JQuery'],
  mobileFrameworks: ['React Native'],
  performanceOptimization: ['SSR', 'PWA'],
  testFrameworks: ['Chai', 'Mocha', 'Jest'],
  buildTools: ['Webpack', 'Gulp'],
  packageManagers: ['npm', 'yarn'],
  dashboardSystems: ['Jira', 'GitHub'],
  DBMS: ['MongoDB', 'MySQL', 'Redis'],
  PMM: ['Scrum', 'Less'],
  VCS: 'Git',
};

JsDeveloper.thingsWantToDevelop = {
  vanillaJs: true,
  reactNative: true,
  nodeJs: true,
  viewLibrary: 'React',
};

JsDeveloper.takeInterestIn = {
  gameDev: true,
  vueJs: true,
  AWS: true,
};
```
