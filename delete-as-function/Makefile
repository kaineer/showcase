PM=pnpm

all: install build run

install:
	${PM} install 2>/dev/null >/dev/null

build:
	npx webpack ./src/index.js 2>/dev/null >/dev/null

run:
	node ./dist/main.js

