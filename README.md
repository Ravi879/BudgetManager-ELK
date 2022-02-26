
# BudgetManager-ELK

This repository contains the demo of [ELK stack](https://www.elastic.co/what-is/elk-stack) for my [BudgetManager-React-Spring-Boot](https://github.com/Ravi879/BudgetManager-React-Spring-Boot) project.

## Screenshot

1. Kibana Dashboard
![Screenshot 1](https://github.com/Ravi879/BudgetManager-ELK/blob/main/screenshot/Kibana-dashboard.png "")

## Built With

- Elasticsearch 7.5.2
- Logstash 7.5.2
- Kibana 7.5.2

## Prerequisites

* Java 8
* [app-log.log](https://www.elastic.co/what-is/elk-stack) file having logs in below pattern(I have added all logs in [spring-boot](https://github.com/Ravi879/BudgetManager-React-Spring-Boot/tree/master/spring-boot) project in below standard)
> [IP] [METHOD] [URIPATH] [TIMESTAMP] [LOGLEVEL] [---] [THREAD] [---] [CLASS] [:] [USERACTION] [--] [ACTIONKEY] [--] [any number of key-pair values, like(vaiable=value)]
* Install Elasticsearch, Logstash and Kibana and setup environment variables
![Screenshot 2](https://github.com/Ravi879/BudgetManager-ELK/blob/main/screenshot/Environemt-variables.png "")

## Open and Run Project

1. open command prompt and run command "elasticsearch"
2. open new command prompt and run command "kibana"
3. open new command prompt and run "logstash -f BudgetManager.conf"

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- This project is licensed under the **[MIT license](http://opensource.org/licenses/mit-license.php)**.


## Support

Please feel free to submit [issues](https://github.com/Ravi879/BudgetManager-ELK/issues) with any bugs or other unforeseen issues you experience.


## Author

- Ravi Gadhiya <br/>

[![alt text][1.1]][1]
[![alt text][2.1]][2]
[![alt text][3.1]][3]

[1.1]: https://github.com/paulrobertlloyd/socialmediaicons/blob/main/linkedin-24x24.png (LinkedIn)
[2.1]: https://github.com/paulrobertlloyd/socialmediaicons/blob/main/github-24x24.png (Github)
[3.1]: https://github.com/paulrobertlloyd/socialmediaicons/blob/main/email-24x24.png (Email)

[1]: https://www.linkedin.com/in/gadhiyaravi
[2]: https://github.com/Ravi879
[3]: mailto:gadhiyaravi87@gmail.com


### Thanks

Please, let me know if this project is useful to you or give suggestions at gadhiyaravi879@gmail.com. I would loved to hear from you guys.
Happy coding. 😊


<!-- credits for adding social media icons -->
<!-- Grab your social icons from https://github.com/carlsednaoui/gitsocial -->
<!-- socialmediaicons https://github.com/paulrobertlloyd/socialmediaicons -->
