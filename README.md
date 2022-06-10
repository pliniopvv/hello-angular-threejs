# hello-angular-three
Repositório utilizado para primeira prática com o Three.JS
- <a href="https://medium.com/geekculture/hello-cube-your-first-three-js-scene-in-angular-176c44b9c6c0">Link do Tutorial</a>

Passos importantes do tutorial:
```powershell
npm install --save three
npm install --save @types/three
ng generate component cube # componente com o canva para renderização do Three.JS
```

deploy gh-pages: <a href="https://medium.com/tech-insights/how-to-deploy-angular-apps-to-github-pages-gh-pages-896c4e10f9b4#:~:text=After%20building%20the%20App%2C%20you%20can%20now%20deploy,the%20place%20of%20%E2%80%9CProject-name%E2%80%9D%20in%20the%20command%20above.">Tutorial</a>
```powershell
npm i angular-cli-ghpages --save-dev
ng build --prod --base-href "https://pliniopvv.github.io/hello-angular-threejs/"
npx angular-cli-ghpages --dir=dist/hello-angular-threejs
```
