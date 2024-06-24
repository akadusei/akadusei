*Hi there 👋 Really nice to meet you...*

## About Me

I have over 10 years experience designing and developing for the web. I started as a Web Developer in 2011 when I co-founded a web services agency with a few friends. My main role was leading that cross-functional team to provide web-based solutions to customers. I also built websites, mostly using custom WordPress themes and plugins we developed in-house.

In 2017, I started a new web hosting business, as a freelancer, called [GrottoPress](https://www.grottopress.com). My role at GrottoPress spans from Systems Engineering, DevOps & SRE, to Full Stack Web Development. I also handle Accounting and other administrative tasks.

I have a strong background in Cybersecurity, and have designed and built solutions that secure software systems at different levels of the web stack.

I am very passionate about solving problems with code, and value relationships that foster growth through learning, and especially ones that are not afraid to try something new.

In my spare time, I like to explore emerging technology, especially new programming languages. I also like to solve code challenges, watch movies, and travel once in a while.

## Current Role

I currently work as a freelance Web & Systems Engineer, building and running a [WordPress PaaS application](https://platform.grottopress.com). This application allows web designers and content creators to launch WordPress websites easily, without having to configure or manage their own servers.

My work involves designing and building new features, and finding and fixing bugs. Any changes are pushed upstream by a CI/CD pipeline that automatically deploys changes into production a few times per day.

The platform is a multi-service application, consisting of 3 apps hosted on separate subdomains. Each app consists of a JSON API backend, a background worker, and a decoupled frontend user interface. The apps are connected via an authentication protocol I designed on top of OAuth2 called [Samba](https://github.com/grottopress/samba). They communicate at the backends through message queues and asynchronous webhooks using [Mel](https://github.com/grottopress/mel).

All the services are hosted on a compute cluster I built on Hetzner Cloud, using Docker Swarm and Traefik. They connect to remote CockroachDB databases and redis stores from third party cloud providers.

I also take care of provisioning, setting up and maintaining the remote virtual machines onto which the platform application deploys WordPress instances. Every WordPress instance launched is automatically deployed and set up inside LXD containers on these machines, ready with free SSL/TLS, and a `.grottopress.net` subdomain for sites that do not have a custom domain.

## Open Source

I am a huge fan of open source. I use, maintain and/or contribute to various projects, both at work and in my free time. Find my open source work on GitHub at the [@GrottoPress](https://github.com/grottopress) organization.

## Connect With Me

- Email: <a@grottopress.com>
- Twitter: [@GrottoPress](https://twitter.com/grottopress), [@akadusei](https://twitter.com/akadusei)
- LinkedIn: [akadusei](https://www.linkedin.com/in/akadusei/)
- GitHub: [@GrottoPress](https://github.com/grottopress), [@akadusei](https://github.com/akadusei)
