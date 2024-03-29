### Creative JavaScript Developer CV (Combo 💣🌶🔝👍😉)

```js
class JsDeveloper {
  constructor() {
    this.teamName = '';
  }

  static checkIsClientSide() {
    return typeof window === 'object';
  };

  static checkIsOfferAwesome(offer) {
    // TODO add more checkers;
    return Boolean(offer);
  }

  updateProfile({ teamName }) {
    this.teamName = teamName;
  }

  shareProfile() {
    const profile = 'https://www.linkedin.com/in/max-marinich';
    JsDeveloper.checkIsClientSide()
      ? window.open(profile)
      : console.log(`Profile: ${profile}`);
  }

  joinTeam({ offer, teamName }) {
    if (JsDeveloper.checkIsOfferAwesome(offer)) {
      this.updateProfile({ teamName });
      this.shareProfile();
    }
  }
}

JsDeveloper.defaultSkills = {
  devFormats: ['ES6', 'TypeScript', 'Solidity'],
  blockchains: ['Ethereum', 'BSC'],
  viewFrameworks: ['React', 'Vue', 'Angular', 'JQuery'],
  mobileFrameworks: ['React Native', 'Native Script'],
  htmlPreprocessors: ['Jade', 'Pug', 'EJS'],
  cssPreprocessors: ['Sass', 'Less', 'Stylus'],
  performanceOptimization: ['SSR', 'PR', 'PWA'],
  testFrameworks: ['Chai', 'Mocha', 'Jest'],
  buildTools: ['Webpack', 'Gulp'],
  packageManagers: ['npm', 'yarn'],
  dashboardSystems: ['Jira', 'GitHub'],
  DBMS: ['MongoDB', 'MySQL', 'Redis'],
  PMM: ['Scrum', 'Less', 'Kanban'],
  VCS: 'Git',
};

JsDeveloper.thingsWantToDevelop = {
  nodeJs: true,
  vanillaJs: true,
  viewLibrary: 'React',
  web3: ['DApp', 'DeFi'],
};

JsDeveloper.takeInterestIn = {
  gameDev: true,
  reactNative: true,
  vueJs: true,
  AWS: true,
};

```
