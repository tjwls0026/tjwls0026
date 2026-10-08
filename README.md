<a href="https://www.gitanimals.org/en-US?utm_medium=image&utm_source=tjwls0026&utm_content=farm">
<img
  src="https://render.gitanimals.org/farms/tjwls0026"
  width="600"
  height="300"
/>
</a>

<h1>깃연결</h1>

<h3>최초 연결</h3>

```bash
git init
git remote add origin https://github.com/tjwls0026/rememind.git
git pull origin main --allow-unrelated-histories
```

<h3>커밋 및 푸시</h3>

```bash
git add .
git commit -m "first commit"
git branch -m master main   # 1회만 사용
git push -u origin main
```

<h3>jsx/tsx 프로젝트 만들기</h3>
```bash
npm create vite@latest rememind -- --template react
npm create vite@latest rememind -- --template react-ts
```
