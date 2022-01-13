![](./assets/banner.svg)

# Hello there, I am Quy <img src="./assets/myprofile.jpeg" width="50">

![visitors](https://visitor-badge.glitch.me/badge?page_id=github.com/RobDoan)
![Linkedin: quydoan](https://img.shields.io/badge/-quydoan-blue?logo=linkedin&link=https://www.linkedin.com/in/quy-doan-56516512/)
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
    def initialize(name: , experience:, company: )
      @name = name
      @experience = experience
      @company = company
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
<!--END_SECTION:waka-->
