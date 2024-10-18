## Description

Backend des Notenplaner Projekts, basierend auf [NestJS](https://nestjs.com/).

## Project setup

Öffne ein Terminal im Projektordner (`/backend`) und führe folgende Befehle nacheinander aus:

```bash
$ npm install
$ cp .env.example .env
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode (mehr logging)
$ npm run start:dev
```

Für die Entwicklung sollte das Projekt immer im "Watch Mode" gestartet werden. Der Standardport ist `3000`, sofern nicht anders in der `.env`-Datei spezifiziert.

## Wie teste ich die API?

- Free & Open Source REST Client: [Bruno](https://www.usebruno.com/)
  - Nach Installation einfach auf die drei Punkte oben links klicken -> "Open Collection" und dann den `.bruno` Ordner im aktuellen Verzeichnis auswählen. Damit werden alle hinterlegten Routen automatisch importiert.

## Resources

Check out a few resources that may come in handy when working with NestJS:

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).


## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
