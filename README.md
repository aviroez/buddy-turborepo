# Turborepo for Ebuddy Test

This is a starter for turborepo EBUDDY PTE. LTD. Technical Test.

## Using this example

Run the following command:

```sh
git clone git@github.com:aviroez/buddy-turborepo.git
cd buddy-turborepo
git checkout main
npm install
```

## Create Backend

This Turborepo inside directory `buddy-turborepo/apps`:
```sh
git clone git@github.com:aviroez/backend-repo.git backend
cd backend
git checkout main
npm install
```
Continue setup on [https://github.com/aviroez/backend-repo](https://github.com/aviroez/backend-repo)

## Create Frontend

This Turborepo inside directory `buddy-turborepo/apps`:
```sh
git clone git@github.com:aviroez/frontend-repo.git frontend
cd frontend
git checkout main
npm install
```
Continue setup on [https://github.com/aviroez/frontend-repo](https://github.com/aviroez/frontend-repo)

### Build

To build all apps and packages, run the following command:

```sh
npm build
```

### Develop

To develop all apps and packages, run the following command:

```sh
npm dev
```