<h1 align="center">Hi 👋, I'm Armin Sayar</h1>
<h3 align="center">A WEB Developer</h3>
</br>
```js
import {FrontEndDeveloper, Other} from 'arminsayar';

function socialMediaAccounts(domain){
  return `https://www.${domain}`
}

class Bio extends FrontEndDeveloper {
  name     = 'Armin Sayar';
  title    = 'Front-End Developer';
  location = 'Tehran, Iran';
  linkedIn = socialMediaAccounts(linkedin.com/in/arminsayar/);
  portfolio = socialMediaAccounts(arminsayar.ir/);
}

class Skills extends FrontEndDeveloper {
  languages  = ['HTML', 'CSS', 'JavaScript', 'TypeScript'];
  frameworks = ['React.js', 'React Native', 'Electron.js', 'Next.js', 'Bootstrap', 'Tailwind'];
  other = ['SCSS', 'jQuery', 'Styled-Components', 'Unit Test' , 'Rest API'];
  versionControls = ['Git', 'Github' , 'Gitlab'];
  packageManagers = ['Webpack', 'babel'];
}

class Skills extends Other {
  languages  = ['Python', 'C', 'C++', 'C#', 'PHP'];
  frameworks = ['Django', 'Express.js'];
  databases = ['SQLite', 'MongoDB', 'MySQL'];
  monitoring = ['Sentry'];
  devOps = ['Docker', 'Nginx'];
}
```



