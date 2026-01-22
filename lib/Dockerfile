FROM ghcr.io/cirruslabs/flutter:stable

WORKDIR /app

COPY pubspec.yaml ./

RUN flutter pub get

COPY . .

RUN flutter build web
