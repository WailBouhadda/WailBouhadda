### Hi there 👋

👋 Hi there! I'm Wail Bouhadda, a passionate data science student 📊🔍. 

🎓 Currently pursuing my data science journey, I'm enthusiastic about extracting insights from data, building predictive models, and exploring the world of AI. 

💻 On a quest to learn, innovate, and collaborate, you'll find my repositories filled with data analysis projects, machine learning experiments, code adventures, and also web development projects. 

🌟 Let's connect and learn together! Feel free to reach out for collaboration or data-related discussions.

<hr>

📧 Email: wailbouhadda31@gmail.com
🌐 LinkedIn: www.linkedin.com/in/wailbouhadda

Happy coding! 🚀


- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.WailBouhadda }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
