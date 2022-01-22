# Storyteller

*Anyone* can create interactive stories with multiple endings!

1. Sign up at [storyteller.page](https://storyteller.page)
2. Click "Create Story"
3. Write a story that leads down multiple paths

Now you have an interactive story!

<img width="600" alt="storyteller" src="https://user-images.githubusercontent.com/364330/150650948-3e5cbca7-8947-4661-b294-7fd592a3b5a3.png">

## Run this app locally

```bash
# clone the repo
git clone https://github.com/panphora/storiess-remake-app.git

# switch into the directory
cd storiess-remake-app

# install dependencies
npm install

# create a .remake file with some basic options
echo -e '{\n  "port": 3000,\n  "sessionSecret": "Vw8bqAxeeqerwerweE2D1EXPyJMdik"\n}' >> .remake

# start the app
npm run dev
```
