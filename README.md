### メモ
```bash
# lint
$ npm run lint

# Format with Prettier
$ npm run format

# controllerの作成
$ nest g controller <controller-name>

# serviceの作成
$ nest g service <service-name>

```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## TypeORM migration
```bash
# migrationの作成
$ npx typeorm migration:generate -n <migration-name>

# migrationの実行
$ npx typeorm migration:run

# migrationのrevert(rollback)
$ npx typeorm migration:revert

# migrationの確認
$ npx typeorm migration:show

# migrationのステータス確認
$ npx typeorm migration:show -p <migration-path>

# drop database
$ npx typeorm schema:drop

```

## JWT
デバックには、[jwt.io](https://jwt.io/)を使用すると便利  