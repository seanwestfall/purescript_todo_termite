### Prerequisites

- psc-0.10.*
- pulp-10.0.*
- bower
- npm

### Building and Running

```sh
bower i
npm i
pulp browserify --to html/index.js
cd html
python -m SimpleHTTPServer # or any other http server
```

now go to: [localhost:8000](http://localhost:8000)
