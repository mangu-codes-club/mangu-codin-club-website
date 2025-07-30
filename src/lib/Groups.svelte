<script lang="ts">
    // Import images for each group
    import backendImage from '../assets/clubs_images/backend.jpeg';
    import frontendImage from '../assets/clubs_images/frontends.avif';
    import hackingImage from '../assets/clubs_images/hacking.webp';
    import embeddedImage from '../assets/clubs_images/embededsystems.jpeg';
    import gamedevImage from '../assets/clubs_images/gamedev.avif';
</script>


<section>
    <div class = 'club_groups'>
        <h2 class = 'main_title'>How We Work</h2>
        <p class = 'groups_intro'>
            The way coding club approaches learning is simple and efficient.We break into groups
            each dealing with its own unique aspect.As of now the club has the following groups</p>
    </div>

    <div class = 'groups_backend'>
        <img class = 'project_group_image' src="{backendImage}" alt="Backend_photo">
        <div>
            <h2 class = 'group_name'>Backend 💻</h2>
            <p class = 'about_groups'>
                languages to harnessing the power of next-generation databases, we do it all. We craft our own large language models and write code that turns imagination into reality.
                <br>Welcome to Mangu Coding Club – Backend, where innovation begins.
            </p>
        </div>
    </div>

    <div class = 'groups_frontend'>
        <div>
            <h2 class = 'group_name'>Frontend 📱</h2>
            <p class = 'about_groups'>
                In Frontend, we design the future of user experience. From sleek interfaces to lightning-fast interactions, we bring creativity and technology together. Using the latest frameworks and tools, we craft designs that don’t just look amazing—they perform flawlessly.
                <br>Welcome to Mangu Coding Club – Frontend, where design meets innovation.
            </p>
        </div>
        <img class = 'project_group_image' src="{frontendImage}" alt="Frontend_photo">
    </div>

    <div class = 'groups_hacking'>
        <img class = 'project_group_image' src="{hackingImage}" alt="Cyber_Security_photo">
        <div>
            <h2 class = 'group_name_hacking'>Ethical Hacking & Cyber Security 👨🏼‍💻</h2>
            <p class = 'about_groups'>
                In Cybersecurity, we are the guardians of the digital realm. From penetration testing to ethical hacking, we learn how to break systems—so we can make them stronger. We fight vulnerabilities with knowledge and defend against tomorrow’s threats today.
                <br>Welcome to Mangu Coding Club – Cybersecurity, where security meets skill.
            </p>
        </div>
    </div>

    <div class = 'groups_embeded'>
        <div>
            <h2 class = 'group_name'>Embeded Systems 🤖</h2>
            <p class = 'about_groups'>
                In Embedded Systems, we bring intelligence to hardware. From microcontrollers to IoT solutions, we build smart devices that interact with the world. Combining electronics and code, we turn concepts into connected innovations.
                <br>Welcome to Mangu Coding Club – Embedded Systems, where hardware comes alive.
            </p>
        </div>
        <img class = 'project_group_image' src="{embeddedImage}" alt="Embeded_Systems_photo">
    </div>

    <div class = 'groups_gamedev'>
        <img class = 'project_group_image' src="{gamedevImage}" alt="Game_Development_photo">
        <div>
            <h2 class = 'group_name_gamedev'>Game Development 🎮</h2>
            <p class = 'about_groups'>
                In Game Development, imagination becomes reality. From stunning 2D worlds to immersive 3D adventures, we create interactive experiences powered by cutting-edge engines and creativity. We don’t just play games—we build them.
                <br>Welcome to Mangu Coding Club – Game Development, where fun meets innovation.
            </p>
        </div>
    </div>

</section>

<style>
    .club_groups{
        height: 200;
        width: 90%;
        padding: 3rem;
        
        border-radius: 1rem;
        margin-bottom: 5rem;
        margin-left: 4rem;
    }
    .groups_backend{
        height:35rem;
        width: 80%;
        border-radius: 1rem;
        padding: 4rem;
        margin: 5rem auto 5rem 1rem;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .groups_frontend{
        height:35rem;
        width: 80%;
        border-radius: 1rem;
        padding: 4rem;
        margin: 5rem 1rem 5rem auto;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .groups_hacking{
        height:35rem;
        width: 80%;
        border-radius: 1rem;
        padding: 4rem;
        margin: 5rem auto 5rem 1rem;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .groups_embeded{
        height:35rem;
        width: 80%;
        border-radius: 1rem;
        padding: 4rem;
        margin: 5rem 1rem 5rem auto;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .groups_gamedev{
        height:35rem;
        width: 80%;
        border-radius: 1rem;
        padding: 4rem;
        margin: 5rem auto 5rem 1rem;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        display: flex;
        align-items: center;
        gap: 2rem;
    }
    .project_group_image{
        height: 25rem;
        width: 30rem;
        border-radius: 2rem;
        
        padding: 2rem;
    }
    .groups_intro{
        font-size: x-large;
        margin-left: 10rem;
        margin-bottom: 0.5rem;
    }
    h2{
        font-size: xx-large;
    }
    .main_title{
        margin-left: 25rem;
        margin-bottom: 3rem;
        font-size: xx-large;
    }
   

@media (max-width: 900px) {
    .club_groups {
        width: 100%;
        padding: 1.5rem;
        margin-left: 0;
        text-align: center;
    }
    .main_title {
        margin-left: 0;
    }
    .groups_intro {
        margin-left: 0;
        font-size: large;
    }
    .groups_backend,
    .groups_frontend,
    .groups_hacking,
    .groups_embeded,
    .groups_gamedev {
        width: 100%;
        flex-direction: column;
        height: auto;
        margin: 2rem 0;
        padding: 1.5rem;
        text-align: center;
    }

    .project_group_image {
        height: auto;
        width: 90%;
        max-width: 20rem;
        margin: 0 auto 1rem;
    }
    .groups_frontend, .groups_embeded {
        margin: 2rem 0;
    }
}
</style>
