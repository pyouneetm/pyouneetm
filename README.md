<div align="center">
    <img src="./assets/01_header_deck.svg" width="100%" />
</div>

<div id="view" align="center">
    <!-- VIEWS COUNTER -->
    <img src="https://komarev.com/ghpvc/?username=pyouneetm&color=12100E&style=for-the-badge&label=VIEWS&abbreviated=true"/>

<br/>

<div align="center">
    <table>
        <tr>
            <td width="66%" valign="top">
                <img src="./assets/02_term_matrix.svg" width="100%" />
            </td>
            <td width="33%" valign="top">
                <!-- STREAK STATS (From User Snippet) -->
                <a href="https://github.com/pyouneetm">
                    <img src="http://github-readme-streak-stats.herokuapp.com?user=pyouneetm&exclude_days=Mon%2CTue%2CSat&theme=github-dark-dimmed&hide_border=true&bg_color=0D1117&stroke=EBEBEB00&date_format=j%20M%5B%20Y%5D&background=EB545400&excludeDaysLabel=EB545400" width="100%" />
                </a>
            </td>
        </tr>
    </table>
</div>

## 🧬 COGNITIVE ARCHITECTURE & BIO-METRICS

```mermaid
graph TD
    User(PUNEET MISHRA) -->|Bio-Input| Client[React + Three.js Interface]
    Client -->|WebSocket| Lanyard(Lanyard API)
    Client -->|REST| Github(GitHub Data)
    
    subgraph "Neural Processing Unit"
        Client --> Audio[Tone.js / Audio Synthesis]
        Client --> Physics[Verlet Physics Engine]
        Client --> Visuals[GLSL / Vanta.js]
    end
    
    Lanyard -->|Presence| Discord(Discord Status)
    Github -->|Repos| GitData(Portfolio)
```

<div align="center">
    <img src="./assets/05_iso_lab.svg" width="100%" />
</div>

<div align="center">
    <table>
        <tr>
            <td width="50%">
                <h3 align="center">MOLECULAR SKILLS</h3>
                <img src="./assets/03_skill_reactor.svg" width="100%" />
            </td>
            <td width="50%">
                <h3 align="center">NEURAL SYNAPSE</h3>
                <img src="./assets/04_net_graph.svg" width="100%" />
            </td>
        </tr>
    </table>
</div>

## 📡 COMMAND CENTER (SOCIAL UPLINKS)
<div align="center">
    <a href="https://github.com/Pyouneetm"><img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white"></a>
    <a href="https://www.linkedin.com/in/pyouneetm"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
    <a href="https://www.instagram.com/pyouneetm"><img src="https://img.shields.io/badge/INSTAGRAM-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
    <a href="https://twitter.com/pyouneetm"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"></a>
    <a href="https://www.youtube.com/@pyouneetm"><img src="https://img.shields.io/badge/YOUTUBE-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>
    <a href="https://www.reddit.com/user/pyouneetm"><img src="https://img.shields.io/badge/REDDIT-FF4500?style=for-the-badge&logo=reddit&logoColor=white"></a>
    <a href="https://discord.com/users/742458064923459675"><img src="https://img.shields.io/badge/DISCORD-5865F2?style=for-the-badge&logo=discord&logoColor=white"></a>
</div>

<br/>

## 🧪 EXPERIMENT: COSMIC DODGE (PHYSICS CORE)
> *A high-velocity survival simulation leveraging verlet integration and separating axis theorem.*

<details>
<summary><b> ACCESS SOURCE KERNEL </b></summary>

```javascript
// PHYSICS INTEGRATION LOOP
update(dt) {
    this.entities.forEach(e => {
        if(e.type === 'ENEMY') {
            // Apply force vectors & gravity
            e.pos.y += e.vel.y * dt;
            
            // Calculate distance magnitude (Euclidean)
            const dx = this.player.pos.x - e.pos.x;
            const dy = this.player.pos.y - e.pos.y;
            const dist = Math.sqrt(dx*dx + dy*dy);
            
            // Event Horizon Singularity Check
            if(dist < 20) this.triggerSingularity();
        }
    });
}
```
</details>

<div align="center">
    <p><i>"The most incomprehensible thing about the universe is that it is comprehensible." - Albert Einstein</i></p>
    <br/>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=00f3ff&height=100&section=footer&text=END_OF_TRANSMISSION&fontSize=20&fontAlignY=40&animation=fadeIn" width="100%"/>
</div>
