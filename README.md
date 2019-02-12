# URL Shortener

This is Node.js project to create short urls.

## Setup

#### Clone repo
`git clone https://github.com/gerardolopezduenas/shortener.git`

#### Install dependencies
`yarn install`

#### Install adonis-cli
`yarn global add @adonisjs/cli`

#### Run migrations

Run the following command to run startup migrations.

`adonis migration:run`

#### Create ENV file
- Rename .env.example into .env _**NOT COMMIT THIS FILE**_
- Run `adonis key:generate`
- Update database data without your local config

#### Run dev server
`adonis serve --dev`
