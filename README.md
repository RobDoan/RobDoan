![](./assets/banner.svg)

## Hi 👋, I am Quy <img src="./assets/myprofile.jpeg" width="50">

![visitors](https://visitor-badge.glitch.me/badge?page_id=github.com/RobDoan)
[![Linkedin: quydoan](https://img.shields.io/badge/-quydoan-blue?logo=linkedin)](https://www.linkedin.com/in/quy-doan-56516512/)
![Experience](https://img.shields.io/badge/experience-15%20years-success)


### <img src="./assets/myprofile2.webp" width="100"> A little more about me...

```ruby

me = Developer.new(name: 'Quy Doan',
                   experience: '15 years',
                   company: 'Samsung Ads',
                   role: 'Senior Software Developer')

me.extend(FullStackSkills)
me.extend(DevOpsSkills)


class Developer
    attr_reader :name, :experience, :company
    def initialize(name: , experience:, company:, role: )
      @name = name
      @experience = experience
      @company = company
      @role = role
    end
end

module FullStackSkills
    def programing_languages
      %w(ruby javascript typescript html css dart go elixir python)
    end

    def databases
      %w(postgresql redis mongodb firestore mysql cassandra)
    end

    def frameworks
      %w(rails react flutter angular backbone)
    end
    alias_method :libraries, :frameworks

    def webservers
      %w(nginx haproxy puma)
    end
end

module DevOpsSkills
    def devops
      %w(docker k8s openshift helm aws google-cloud concourse heroku)
    end
end

```

### ✨ Award ✨

* 🥈 Startup Weekend - Eco-Social Impact - Montreal, Canada (2018)
* 🥈 Up Hackathon - Health UP Hackathon - Singapore (2013)
* ![Paypal](https://img.shields.io/badge/-Prize-blue?logo=paypal) Hackathon - Santiago, Chile (2013)

----

![github-contribution](https://raw.githubusercontent.com/RobDoan/RobDoan/output/github-contribution-grid-snake.svg)

<!--START_SECTION:waka-->
![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My GitHub Data** 

> 🏆 46 Contributions in the Year 2022
 > 
> 📦 104.6 kB Used in GitHub's Storage 
 > 
> 🚫 Not Opted to Hire
 > 
> 📜 58 Public Repositories 
 > 
> 🔑 27 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: America/Toronto

💬 Programming Languages: 
Ruby                     16 hrs 53 mins      ██████████████████████░░░   88.42% 
Go                       45 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.97% 
SQL                      22 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.99% 
YAML                     15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.38% 
Git                      15 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.31%

🔥 Editors: 
RubyMine                 17 hrs 53 mins      ███████████████████████░░   93.58% 
VS Code                  1 hr 13 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   6.42%

🐱‍💻 Projects: 
Rtb-trader               18 hrs 4 mins       ███████████████████████░░   94.55% 
examples-go-kit          32 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.85% 
Unknown Project          13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.18% 
gin-quick-start          5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44% 
gitlab                   3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.35%

💻 Operating System: 
Mac                      19 hrs 6 mins       █████████████████████████   100.0%

```

**I Mostly Code in Ruby** 

```text
Ruby                     20 repos            ███████████░░░░░░░░░░░░░░   44.44% 
JavaScript               17 repos            █████████░░░░░░░░░░░░░░░░   37.78% 
TypeScript               6 repos             ███░░░░░░░░░░░░░░░░░░░░░░   13.33% 
Elixir                   1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.22% 
Shell                    1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.22%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/RobDoan/RobDoan/main/charts/bar_graph.png) 


 Last Updated on 29/01/2022 18:53:31 UTC
<!--END_SECTION:waka-->
