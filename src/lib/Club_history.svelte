<script lang=ts>
    import anonymus from '../assets/founders/anonymus.png';
</script>

<section>
    <div id = 'club_history_intro' class = 'club_history_intro'>
        <h2>Club History</h2>
        <p class = intro_speech>
            Mang'u Coding Club wasa formed in the year 2024 by three passionate <br /> developers who wanted to give back
            to thecommuninty. <br />They underwent multiple challenges but eventually succeded in officialising the club.
            Later in 2025 the club found a capable patron who could carry the club <br />to greater heights. Mr Waswa 
            together with Collins Thayu , Alvin Ngondo and Ken Karoki begun the journey of coding club.<br>

        </p>
      
    </div>

    <div class = 'Thayu_co_founders_speech'>
        <img class = 'co_founders_image' src="{anonymus}"  alt="Collins Thayu - co-founder">
        <div>
            <h3>Collins Thayu</h3>
            <p>
                This isn’t just another club—it’s a movement. When we founded Mangu Coding Club, we envisioned a community where everyone—regardless of experience—could find a place to learn, grow, and lead.
                <br><br>
    Coding is not just about writing lines of code. It’s about solving problems, thinking critically, and shaping a better future. It’s about teamwork—because the best innovations don’t happen in isolation; they happen when passionate people come together.
                <br><br>
    So, I challenge each one of you: collaborate, ask questions, share your knowledge. This is your platform to innovate, to fail without fear, and to turn ideas into impact.
                <br><br>
    Let’s make Mangu Coding Club the home of tomorrow’s tech leaders. The journey starts now!
            </p>
        </div>
    </div>

    <div class = 'Ken_co_founders_speech'>
        <div>
            <h3>Ken Karoki</h3>
            <p>
                It’s amazing to see so many bright minds gathered here today. When we started Mangu Coding Club, our dream was simple: to create a space where curiosity meets innovation, where ideas are not just discussed—but built.
                <br><br>
    Today, technology is moving faster than ever. From artificial intelligence to blockchain, from cybersecurity to game development, the possibilities are endless. But here’s the truth—opportunities don’t just come; they’re created by those who dare to build.
                <br><br>
    Our mission is to be those creators. To learn, to experiment, to fail fast, and to rise even stronger. Whether you’re passionate about coding, security, AI, or building the next big app, this is your home. Together, we’ll push boundaries and show the world what the Mangu spirit of excellence truly means.
                So, let’s get started. Let’s build, let’s learn, and let’s make an impact that lasts.
            </p>
        </div>
        <img class= 'co_founders_image' src="{anonymus}" alt="Ken Karoki - co-founder">
    </div>

    <div class= 'Alvin_co_founders_speech'>
        <img class= 'co_founders_image' src="{anonymus}" alt="Alvin Ngondo - co-founder">
        <div>
            <h3>Alvin Ngondo</h3>
            <p>
                When we talk about technology, we often think about big companies—Google, Tesla, OpenAI—but guess what? Every one of those giants started with a small group of people, united by passion. That’s exactly what we have here.
                <br><br>
    Technology is not magic—it’s creativity, curiosity, and consistency. Here at Mangu Coding Club, we believe in building, not just consuming. Whether it’s AI, game development, cybersecurity, or embedded systems—we’re here to create, innovate, and challenge what’s possible.
                <br><br>
    So dream big. Code bigger. And remember: this is just the beginning. The next breakthrough could come from right here, from you.
                <br><br>
    Let’s make history together!
            </p>
        </div>
    </div>

    <div class = 'Waswa_co_founders_speech'>
        <div>
            <h3>Simon Wekesa</h3>
            <p>
                It is a true honor to say as the first patron of the Mangu Coding Club—a club that began as a spark of curiosity and has grown into a beacon of innovation in our school.
                <br><br>
    When this journey started, the vision was clear: to give students the tools, the confidence, and the mindset to thrive in the digital age. I have watched these young pioneers—Ken Karoki, Collins Thayu, and Alvin Ngondo—turn an idea into a movement, and I couldn’t be prouder.
                <br><br>
    In the early days, resources were few, challenges were many, and doubts were everywhere. But what set this club apart was its resilience. These students didn’t just talk about technology—they lived it. They stayed late, learned new languages, built projects, and most importantly, created a culture of collaboration and innovation.
                <br><br>
    To the new members here today, let me tell you this: the future is not something you wait for—it is something you create. Coding is more than writing code; it’s about problem-solving, creativity, and perseverance. Every great invention started with a student just like you, willing to take that first step.
                <br><br>
    As your patron, my message is simple: keep pushing boundaries. Ask questions. Take risks. And never underestimate the power of a single line of code—it can change the world.
                <br><br>
    Congratulations to the founders, the team, and everyone who believed in this dream. The journey has just begun, and I cannot wait to see the heights this club will reach.
            </p>
        </div>
        <img class= 'co_founders_image' src="{anonymus}" alt="Simon Wekesa - first patron">
    </div>
</section>

<style>
    .club_history_intro{
        padding: 3rem;
        border-radius: 1rem;
        margin-bottom: 5rem;
        text-align: center;
    }
    .Thayu_co_founders_speech{
        min-height:30rem;
        height: auto;
        width: 80%;
        border-radius: 1rem;
        padding: 3rem;
        margin: 5rem auto 5rem 1rem;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .Ken_co_founders_speech{
        min-height:30rem;
        height: auto;
        width: 80%;
        border-radius: 1rem;
        padding: 3rem;
        margin: 5rem 1rem 5rem auto;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .Alvin_co_founders_speech{
        min-height:30rem;
        height: auto;
        width: 80%;
        border-radius: 1rem;
        padding: 3rem;
        margin: 5rem auto 5rem 1rem;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .Waswa_co_founders_speech{
        height:auto;
        width: 80%;
        border-radius: 1rem;
        padding: 3rem;
        margin: 5rem 1rem 5rem auto;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .co_founders_image{
        height: 20rem;
        width: 20rem;
        border-radius: 2rem;
        padding: 2rem;
        object-fit: cover;
    }
    .intro_speech{
        font-size: x-large;
        margin: 0 auto;
        max-width: 80ch;
    }
    h2{
        margin-bottom: 3rem;
        font-size: xx-large;
    }
h3{
        margin-bottom: 1rem;
    
        font-size: x-large;
    }


    @media (max-width: 900px) {
    .Thayu_co_founders_speech,
    .Ken_co_founders_speech,
    .Alvin_co_founders_speech,
    .Waswa_co_founders_speech {
        width: 100%;
        flex-direction: column;
        margin: 2rem 0;
        padding: 1.5rem;
        text-align: center;
    }
    .Ken_co_founders_speech, .Alvin_co_founders_speech, .Waswa_co_founders_speech {
        margin: 2rem 0;
    }

    .co_founders_image {
        margin: 0 auto 1rem;
        height: 15rem;
        width: 15rem;
    }

    .intro_speech {
        font-size: large;
    }
}
</style>
