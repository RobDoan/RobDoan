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
![Profile Views](http://img.shields.io/badge/Profile%20Views-10-blue)

**🐱 My GitHub Data** 

> 🏆 46 Contributions in the Year 2022
 > 
> 📦 104.7 kB Used in GitHub's Storage 
 > 
> 🚫 Not Opted to Hire
 > 
> 📜 58 Public Repositories 
 > 
> 🔑 28 Private Repositories  
 > 
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: America/Toronto

💬 Programming Languages: 
Ruby                     10 hrs 33 mins      ███████████████████░░░░░░   78.77% 
YAML                     1 hr 53 mins        ███░░░░░░░░░░░░░░░░░░░░░░   14.07% 
Text                     11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.38% 
Markdown                 8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.0% 
GitIgnore file           6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.82%

🔥 Editors: 
RubyMine                 13 hrs 24 mins      █████████████████████████   99.99% 
VS Code                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01%

🐱‍💻 Projects: 
Rtb-trader               7 hrs 20 mins       █████████████░░░░░░░░░░░░   54.7% 
samsung_ads-auto_deploy  4 hrs 55 mins       █████████░░░░░░░░░░░░░░░░   36.67% 
auto-deploy              44 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.48% 
veracode-api-wrapper     10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.36% 
crystalball              8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.03%

💻 Operating System: 
Mac                      13 hrs 24 mins      █████████████████████████   100.0%

```

**I Mostly Code in Ruby** 

```text
Ruby                     21 repos            ███████████░░░░░░░░░░░░░░   45.65% 
JavaScript               17 repos            █████████░░░░░░░░░░░░░░░░   36.96% 
TypeScript               6 repos             ███░░░░░░░░░░░░░░░░░░░░░░   13.04% 
Elixir                   1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.17% 
Shell                    1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.17%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/RobDoan/RobDoan/main/charts/bar_graph.png) 


 Last Updated on 07/02/2022 18:45:00 UTC
<!--END_SECTION:waka-->
