<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
 
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li> 
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Producer and consumer using RabbitMQ, .NET Projects

This is a basic project of a consumer (.net console application) and a producer .NET Api.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With 

* [![NET 8][NET-8]][NET-url]
* [![EF Core][ef-core]][ef-core-url]
* [![RABBITMQ][RABBITMQ]][RABBITMQ-url] 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
 

### Prerequisites

* NET 8.
* RabbitMQ.
* SQL Server.
 
   

### Installation

Generate migration and apply (EF Core):
* migration efcore
  ```console
  add-migration "initial"
  update-database

  ```

Get rabbitmq image:
* rabbitmq
  ```console
  docker pull rabbitmq:3-management

  ```
Create container of rabbitmq image:
* rabbitmq
  ```sh
  docker run --rm -it -p 15672:15672 -p 5672:5672 rabbitmq:3-management

  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Absalon Blanco - absalon.blanco@hotmail.com
 
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
 
* [c-sharpcorner](https://www.c-sharpcorner.com/article/rabbitmq-message-queue-using-net-core-6-web-api/) 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->  
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/absalonblanco/ 
[NET-8]: https://img.shields.io/badge/8-20232A?style=for-the-badge&logo=dotnet&logoColor=white
[NET-url]: https://learn.microsoft.com/en-us/dotnet/fundamentals/
[ef-core]: https://img.shields.io/badge/ef_core-20232A?style=for-the-badge&logo=databricks&logoColor=61DAFB
[ef-core-url]: https://learn.microsoft.com/en-us/ef/core/
[RABBITMQ]: https://img.shields.io/badge/rabbitmq-white?style=for-the-badge&logo=rabbitmq&logoColor=orange
[RABBITMQ-url]: https://vuejs.org/ 