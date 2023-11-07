# OpenTelemetry Project

to start this POC run

`docker run -d -p 9411:9411 openzipkin/zipkin`
or use `docker-compose up -d` in ./goapp

to start a zipkin container

---- NODEJS MS ----

#`npm i`
to install the packages

#`node courses.js`
in one tab

#`node dashboard.js`
in another tab

then visit localhost:3001/dashboard

--- GOLANG MS ---

in ./goapp

go run main.go

localhost:8888

---

Now view the tracing data in zipkin : http://localhost:9411/zipkin/


https://zipkin.io/

https://github.com/open-telemetry

https://github.com/open-telemetry/opentelemetry-collector