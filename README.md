# ts_express_boilerplate

大体ここ: https://qiita.com/notakaos/items/3bbd2293e2ff286d9f49#6-hello-world
Lint: https://qiita.com/yuukive/items/012bdf1b9ff3881546b3

scripts:
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "ts-node src/index.ts",
    "dev:watch": "ts-node-dev --respawn src/index.ts",
    "clean": "rimraf dist/*",
    "tsc": "tsc",
    "build": "npm-run-all clean tsc",
    "start": "node .",
    "lint": "tslint --exclude **/*.d.ts --project . --fix 'src/**/*.ts' 'test/**/*.ts'"
