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
![Profile Views](http://img.shields.io/badge/Profile%20Views-97-blue)

**🐱 My GitHub Data** 

> 🏆 41 Contributions in the Year 2022
 > 
> 📦 103.3 kB Used in GitHub's Storage 
 > 
> 🚫 Not Opted to Hire
 > 
> 📜 57 Public Repositories 
 > 
> 🔑 27 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: America/Toronto

💬 Programming Languages: 
Markdown                 2 hrs 40 mins       ██████████████████░░░░░░░   73.69% 
YAML                     23 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   10.78% 
Dart                     19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.03% 
Ruby                     14 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.5%

🔥 Editors: 
VS Code                  3 hrs 6 mins        █████████████████████░░░░   85.75% 
Android Studio           19 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.03% 
RubyMine                 11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.23%

🐱‍💻 Projects: 
profile                  3 hrs 6 mins        █████████████████████░░░░   85.75% 
BlackHole                18 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.56% 
lamar-cms                11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.23% 
fluturant_table_menu     1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.46%

💻 Operating System: 
Mac                      3 hrs 37 mins       █████████████████████████   100.0%

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


 Last Updated on 14/01/2022
<!--END_SECTION:waka-->
