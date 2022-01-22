# Storyteller

*Anyone* can create interactive stories with multiple endings!

1. Sign up at [storyteller.page](https://storyteller.page)
2. Click "Create Story"
3. Write a story that leads down multiple paths

Now you have an interactive story!

<img width="600" alt="storyteller" src="https://user-images.githubusercontent.com/364330/150650948-3e5cbca7-8947-4661-b294-7fd592a3b5a3.png">

## Run this app locally

```
git clone https://github.com/panphora/storiess-remake-app.git
cd storiess-remake-app
npm install
# you need a .remake file with some basic options specified:
echo -e '{\n  "port": 3000,\n  "sessionSecret": "Vw8bqAxeeqerwerweE2D1EXPyJMdik"\n}' >> .remake
npm run dev
```
