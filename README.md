# Monitoring-And-Log-Demo-Spring-Boot

This Repository demonstrates the setup of Monitoring using Actuator, Prometheus, Grafana and Logging System using Log4j for the SpringBoot project.


# Steps to Add Monitoring
<ul>
    <li>Generate SpringBoot Project from https://start.spring.io/</li>
    <li>
        Add Dependencies
        <ol>
            <li>spring-boot-devtools - Spring Boot DevTools pick up the changes and restart the application </li>
            <li>spring-boot-starter - There are around 50+ Spring Boot Starters for different Spring and related technologies. These starters give all the dependencies under a single name </li>
            <li>spring-boot-starter-web - Spring Boot DevTools pick up the changes and restart the application </li>
            <li>spring-boot-starter-actuator - Actuator is mainly used to expose operational information about the running application — health, metrics, info, dump, env, etc. It uses HTTP endpoints or JMX beans to enable us to interact with it.</li>
        </ol>
    </li>
    <li>
        Add configuration for actuators in application.properties then open : http://localhost:8080/actuator
        <ol>
            <li>management.endpoints.web.exposure.include=*</li>
            <li>management.endpoints.health.show-details=always</li>
        </ol>
    </li>
</ul>


# Help
<ul>
    <li>
        add "--spring.profiles.active=development" in environment.
    </li>
    <li>
        git remote set-url origin https://parvezmullah@github.com/parvezmullah/Monitoring-And-Log-Demo-Spring-Boot.git
    </li>
</ul>

