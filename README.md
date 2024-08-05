### Hi there 👋, my name is Sangpil Jung
#### I am a Full-Stack developer at Mosafe.

## Skills and Experience 

using System;
using System.Collections.Generic;

public class Person
{
    private string name;
    private string major;
    private int graduationYear;

    public Person()
    {
        this.name = "Sangpil Jung";
        this.major = "Computer Science/Information Technology";
        this.graduationYear = 2021;
    }

    public void SayHello()
    {
        Console.WriteLine("Hey, thank you for visiting my GitHub profile!");
    }

    public void ShowAbilities()
    {
        // My programming language specialties
        string[] programmingLanguages = {
            "Python", "C Sharp",
            "JavaScript", "HTML/CSS", 
            "PHP"
        };

        // Tech stacks, Frameworks, Libraries
        string[] techStacks = {
            // Python
            "Pandas", "NumPy", "Sci-Kit", "TensorFlow",
            "BeautifulSoup", "Selenium", "Flask", "huggingface",
            "transformers", "gradio"
            
            // JavaScript
            "ReactJS", "React Native", "Node.js"
            
            // PHP
            "Elementor custom widget"

            // Jquery
            "scripts"
            
            // SQL
            "MySql" 
            
            // Non-relational-db
            "Mongo Db"

            // style
            "Material UI", "Tailwind Css", "Sass", "Bootstrap"
        };
    }

    public List<string> GetMyInterests()
    {
        List<string> interests = new List<string>();

        interests.Add("Artificial Intelligence / Machine Learning");
        interests.Add("Algorithm & Engineering");
        interests.Add("Brazilian Jiu-jitsu");

        return interests;
    }

    public PriorityQueue<string, string> GetMyHobbies()
    {
        PriorityQueue<string, string> hobbies = new PriorityQueue<string, string>();

        hobbies.Enqueue("Work out", "Work out");
        hobbies.Enqueue("Read books", "Read books");

        return hobbies;
    }








