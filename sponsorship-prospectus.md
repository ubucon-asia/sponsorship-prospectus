---
marp: true
theme: ubucon
paginate: true
title: UbuCon Asia 2026 Sponsorship prospectus
---

<script src="https://unpkg.com/mermaid/dist/mermaid.min.js"></script>
<script>
  // Replaces <pre class="mermaid"> blocks with <img> blocks, to make mermaid render properly.
  // Preserves classes and styling so they can be used to fix sizing if necessary.

  mermaid.initialize({ startOnLoad: false });

  window.addEventListener('load', async function () {
    const mermaidEls = document.querySelectorAll('pre.mermaid');

    for (const el of mermaidEls) {
      const { svg } = await mermaid.render('asd', el.textContent);

      const img = document.createElement('img');
      img.setAttribute('src', `data:image/svg+xml;base64,${btoa(svg)}`);
      img.setAttribute('class', el.getAttribute('class'));
      img.setAttribute('style', el.getAttribute('style') || '');

      el.parentNode.replaceChild(img, el);
    }
  });
</script>

<style scoped>
    section {
        background-image: url(https://assets.ubuntu.com/v1/ed94a429-0000_suru-corner-fan--top-right-light.jpg);
        background-position: top right;
        background-size: 20rem 15rem;
        align-content: end;
        font-size: 40px;
    }
    h1 {
        font-size: 60px;
    }
</style>

![w:200](./assets/2026/uca26logo.svg)

# UbuCon Asia 2026

August 8 - 9
National Taiwan University of Science and Technology
Taipei, Taiwan
**Sponsorship prospectus**

<img src="./assets/2026/ntust.jpg" style="margin-left: -40px; margin-bottom: -50px; width: 210mm; height: 300px; object-fit: cover;">

<!-- _paginate: skip -->

---

<!-- header: ![w:50](./assets/2026/uca26logo.svg) -->
<!-- footer: https://2026.ubucon.asia | sponsorship@ubucon.asia -->


<img src="./assets/2025/uca25_banner_Image.jpg" style="margin-left: -40px; margin-top: -40px;  width: 210mm; height: 300px; object-fit: cover;">

# About UbuCon Asia

**UbuCon(s) (Ubuntu Conference)** are non-profit events organized by Ubuntu Communities worldwide. These events bring together hundreds of Open Source enthusiasts, users, developers, and contributors to share their stories and experiences regarding **Ubuntu** and relevant free and open source technologies for **servers, desktops, cloud computing, IoT, robotics, data science, AI/ML, and much more.**

In the spirit of promoting the love of Ubuntu and Open Source, **UbuCon Asia,** one of the regional UbuCon events **focusing specifically on the Asian region,** is organized annually by Ubuntu Communities and other free and open source communities across Asia. Following the success of previous editions in Seoul (South Korea), Surakarta (Indonesia), Jaipur (India), and Kathmandu (Nepal), we are proud to announce that the **6th edition of UbuCon Asia** will be co-hosted with **COSCUP 2026** at the **National Taiwan University of Science and Technology (NTUST)** in Taipei, Taiwan.

As a non-profit event organized by volunteers without compensation or stable funding, we rely on sponsorships to host these events. Such events enable community members to learn, share, and grow together while meeting many of their peers in person, sometimes for the first time.

## Event overview

- **Event name:** UbuCon Asia 2026 @ COSCUP
- **Dates:** August 8th - 9th
- **Venue:** National Taiwan University of Science and Technology (NTUST), Taipei, Taiwan
- **Participant scale:** Around 300 or more
- **Organizer:** UbuCon Asia Committee

---

# The Ubuntu Project and Its Community

<!-- Text below are draft. You may improve it if you want -->
<div style="display: flex; flex-direction: row; margin-left: -40px; width: 210mm; height: 200px; ">
  <img src="./assets/uca22.JPG" style="flex: 1">
  <img src="./assets/uca23.JPG" style="flex: 1">
  <img src="./assets/2024//uca24.jpg" style="flex: 1">
</div>

## Ubuntu

Ubuntu, co-developed by Ubuntu Community with people from worldwide and Canonical, stands as the world's leading open source linux based operating system. With its mission to bring free software to the widest audience while accelerating innovation and underpinning operations, Ubuntu powers millions of devices from personal computers to cloud infrastructure, serving as the foundation for technological advancement in AI, cloud computing, IoT, and enterprise solutions.

## Ubuntu Community

The Ubuntu community is an international network united by our name's meaning - "humanity towards others." With millions of users and thousands of contributors worldwide, we shape the future of computing through open collaboration and freely shared work. Our diverse community includes developers, engineers, system administrators, researchers, artists, writers, and more all working together to make technology accessible to everyone.

Our community thrives through:

- Active participation across Ubuntu Discourse, Launchpad, GitHub, Matrix chat and more
- Local Community (LoCo) teams advocating across regions
- Technical support and knowledge sharing on Ask Ubuntu and Ubuntu Forums
- Leadership opportunities through Ubuntu Membership and governance
- Commitment to our Code of Conduct and our mission

## UbuCon Asia

UbuCon Asia serves as the premier Ubuntu community event in the Asian region. By sponsoring UbuCon Asia, you're directly supporting Ubuntu's mission while connecting with a dynamic community that drives innovation across Asia and beyond.

---

# Host city & The venue

<hr/>
<div style="display: flex; flex-direction: row; align-items: flex-start;">
    <div style="flex: 1">
    <img src="./assets/2026/taiwan.jpg" style="width: 100%; object-fit: cover;"> 
    <img src="./assets/2026/taipei.jpg" style="width: 100%; object-fit: cover;"> 
    </div>
  <div style="flex: 1; padding-left: 20px;">
    <h2>Taiwan</h2>
    <p style="text-align: justify;">
    Taiwan is a vibrant island nation renowned for its thriving technology industry, world-class semiconductor manufacturing, rich cultural heritage, and warm hospitality. As one of Asia's leading tech hubs, Taiwan is home to global leaders in computing, cloud, and open-source ecosystems, making it an ideal destination for a FOSS focused international conference.
    </p>
    <h2>Taipei</h2>
    <p style="text-align: justify;">
    Taipei is Taiwan's dynamic capital and a global technology center, home to major tech corporations, a thriving startup scene, and a deeply embedded open-source culture. The city offers an ideal blend of modern infrastructure, outstanding cuisine, and excellent connectivity for international travelers.
    </p>
  </div>
</div>
<hr/>
<div style="display: flex; flex-direction: row; align-items: flex-start;">
    <div style="flex: 1">
    <img src="./assets/2026/ntust.jpg" style="width: 100%; object-fit: cover;">
    </div>
  <div style="flex: 1; padding-left: 20px;">
    <h2>National Taiwan University of Science and Technology </h2>
    <p style="text-align: justify;">
    <b>NTUST</b> is one of Taiwan's leading technology universities, located in central Taipei. Its state-of-the-art academic facilities provide an excellent environment for a community driven open-source conference, with large auditoriums, classroom spaces, and exhibition areas.
    </p>
  </div>
</div>

---

# Who attends UbuCon Asia

| Category                  | Roles                                                                                     |
|---------------------------|-------------------------------------------------------------------------------------------|
| **Software Engineers**    | System, Application (Web, Desktop, etc.), Embedded (IoT, Robotics), Kernel & OS           |
| **IT Infra & Operations** | SRE, SysAdmins, Solution Architects, DevOps, Cloud Engineers                              |
| **Data & AI**             | Data Engineers, Data Scientists, DBA, AI/ML Engineers                                     |
| **Community & Leadership**| Community Managers, DevRel, Technical Managers, OSPO Teams                                |
| **Academic & Other**      | Students (IT majors), Professors, Researchers, Analysts, Entrepreneurs, Media             |


## Highlights from last year
UbuCon Asia 2025 was the **largest and most diverse edition** in the conference's history.

<div style="display: flex; flex-direction: row;">
  <p  style="flex: 1"><b>Total ~450</b><br>Participants</p>
  <p  style="flex: 1">Participants from <br><b>14+ countries</b></p>
  <p  style="flex: 1">Session proposals<br><b>73 received</b></p>
  <p  style="flex: 1"><b>40 Speakers</b><br> in total</p>
  <p  style="flex: 1"><b>~40% Attendees</b><br>with career</p>
</div>

### Participants demographics
<pre class="mermaid mermaid-100h">
pie 	
    "Entrepreneur": 9
    "IT Infra & Operations": 49
    "Other": 49
    "Scientist": 15
    "Software Engineers": 67
    "Specialized Roles (CM/AI/Data)": 36
    "Student":	225
</pre>

---
### Demographics breakdown - Software Engineers
<pre class="mermaid mermaid-100h" style="height: 40%">
pie 
    "Backend":	8
    "Fullstack":	5
    "Web":	5
    "Embedded":	3
    "Frontend":	2
    "Other":	44
</pre>

### Demographics breakdown - IT Infra & Operations
<pre class="mermaid mermaid-100h"  style="height: 40%">
pie 
    "DevOps Engineer":	19
    "System Engineer":	6
    "Cloud Engineer":	5
    "IT Operation":	5
    "Network Engineer":	4
    "Support Engineer":	3
    "Security Engineer":	3
    "Other": 4
</pre>
---

# Become a sponsor!

UbuCon Asia, although being a new addition to the UbuCon events, has already been organized in Seoul(South Korea), Surakarta(Indonesia), Jaipur(India), and Kathmandu(Nepal) with many success. It has been a momentum to drive making local Ubuntu communities active or revive and connect with each other. The event is solely organized by community and volunteer efforts without any financial compensation. Thus, we rely solely on our sponsors to fund our various expenses and make the event successful.

Ubuntu is more than just an open-source platform; it embodies a global community committed to diversity, collaboration, and empowerment. UbuCon Asia is a unique opportunity to engage with passionate technology professionals across the Asia. Sponsoring this event will connect you with top Ubuntu developers, contributors, and innovators from diverse Asian communities, gaining insights into the region's vibrant tech ecosystem. Your support will help foster technological exchange and community growth across Asia and beyond.

## Benefits of Sponsorship

<div style="display: flex; flex-direction: row; margin-top: -30px;">
  <div style="flex: 1; padding-right: 10px;">
  <p>
    <img src="./assets/icons/target.svg" style="height: 40px"/><br/>
    <b>Targeted marketing opportunities</b><br/>
    A good opportunity to boost leads through targeted marketing with most of our audience from tech industry.
  </p>
  <p>
    <img src="./assets/icons/talent.svg" style="height: 40px"/><br/>
    <b>Talent acquisition</b><br/>
    Recruit the brightest minds in the industry to fill your open positions.
    40%+ of our attendees last year were with IT related professions. 
  </p>
  <p>
    <img src="./assets/icons/bullhorn.svg" style="height: 40px"/><br/>
    <b>Empower your branding</b><br/>
    Expose your logo on banners, website, videos and more places to empower your branding and awareness.
  </p>
  <p>
    <img src="./assets/icons/brain.svg" style="height: 40px"/><br/>
    <b>Mindshare Capture from<br/>Developers and Advocates</b><br/>
    Position your brand as a key player and a thought leader among influential technical professionals.
  </p>
  </div>
  <div style="flex: 1; padding: 10px;">
  <p>
    <img src="./assets/icons/present.svg" style="height: 40px"/><br/>
    <b>Showcase products and services</b><br/>
    Showcase your innovative products and service face-to-face with your potential and existing customers and receive valuable feedback. 
  </p>
  <p>
    <img src="./assets/icons/speak.svg" style="height: 40px"/><br/>
    <b>Establish thought leadership</b><br/>
    Showcase your expertise on Ubuntu and its ecosystem and educate the community about your organization’s products, services and open source strategies.
  </p>
  <p>
    <img src="./assets/icons/opensource.svg" style="height: 40px"/><br/>
    <b>Support Open source and Community</b><br/>
    Sponsoring our event is one of the best ways to show your sincere and support to open source and community.
  </p>
  <p>
    <img src="./assets/icons/news.svg" style="height: 40px"/><br/>
    <b>Media Exposure and PR Announcements</b><br/>
    Generate strategic media coverage and amplify brand messaging beyond the event.
  </p>
  </div>
</div>

**By sponsoring UbuCon Asia, you get to reach a diverse and varied audience 
of Ubuntu and open source practitioners, all in one place.**


---

# Past sponsors

<div class="imgrow">
  <img src="./assets/previous_sponsor_logos/canonical.svg">
  <img src="./assets/previous_sponsor_logos/onlyoffice.svg">
  <img src="./assets/2025/sponsor_logos/DeepComputing.svg">
</div>
<div class="imgrow">
  <img src="./assets/previous_sponsor_logos/naver_cloud.png">
  <img src="./assets/previous_sponsor_logos/microsoft.png">
  <img src="./assets/previous_sponsor_logos/invesume.png">
</div>
<div class="imgrow">
  <img src="./assets/previous_sponsor_logos/whatap.png">
  <img src="./assets/previous_sponsor_logos/nhncloud.png">
  <img src="./assets/previous_sponsor_logos/nevacloud.png">
</div>
<div class="imgrow">
  <img src="./assets/previous_sponsor_logos/biznet_giocloud.png">
  <img src="./assets/2025/sponsor_logos/logpoint.png">
  <img src="./assets/previous_sponsor_logos/ahnlabcloudmate.svg">
</div>
<div class="imgrow">
  <img src="./assets/previous_sponsor_logos/grometric.svg">
  <img src="./assets/previous_sponsor_logos/elastic.svg">
  <img src="./assets/previous_sponsor_logos/inflearn.svg">
</div>
<div class="imgrow">
  <img src="./assets/2025/sponsor_logos/dishhome.png">
  <img src="./assets/previous_sponsor_logos/nipa.png">
  <img src="./assets/previous_sponsor_logos/indobsd.webp">
</div>
<div class="imgrow">
  <img src="./assets/previous_sponsor_logos/idnic.png">
  <img src="./assets/2025/sponsor_logos/cloud_himalaya.png">
  <img src="./assets/previous_sponsor_logos/fossunited.svg">
</div>

---

<style scoped>
    table {
        font-size: 14px;
    }
</style>

# Sponsorship packages
| Package  | Price (USD) | Official website and OPass app          | Event Site (co-branded with COSCUP)   | COSCUP social media   |
| -------- | ----------- | --------------------------------------- | ------------------------------------- | --------------------- |
| Titanium | 8,500       | Company profile listed; agenda page ads | Logo displayed at the <sup>\*1; \*2; \*3; \*4; \*5; \*6; \*7 </sup> | 1 article on the COSCUP blog; <sup>\*0</sup> |
| Diamond  | 6,090       | Company profile listed; agenda page ads | Logo displayed at the <sup>\*1; \*3; \*5</sup>   | 1 article on the COSCUP blog; promotion via COSCUP social media |
| Gold     | 4,910       | Company profile listed; agenda page ads | Logo displayed at the <sup>\*1; \*3</sup>        | 1 article on the COSCUP blog; promotion via COSCUP social media |
| Silver   | 2,945       | Company profile listed; agenda page ads | Logo displayed at the <sup>\*1</sup>             | Promotion via COSCUP social media                               |
| Bronze   | 1,375       | Company profile listed; agenda page ads | Logo displayed at the <sup>\*1</sup>             | Promotion via COSCUP social media                               |
| Friend   | 785         | Company profile listed                  | Logo displayed at the <sup>\*1</sup>             | Promotion via COSCUP social media                               |

<p></p>

| Additional purchase                 | Titanium | Diamond  | Gold   | Silver | Bronze | Friend |
| ----------------------------------- | -------- | -------- | ------ | ------ | ------ | ------ |
| Booth                               | 2,950    | 2,160    | 980    | X      | X      | X      |
| Main Track, 30 mins                 | 1,608    | 1,608    | X      | X      | X      | X      |
| Technical Talk, 30 mins             | 1,608    | 1,608    | 1,608  | X      | X      | X      |
| Workshop, 2 hrs                     | 983      | 983      | 983    | X      | X      | X      |
| Logo on stage flag in keynote hall  | Included | 3,930    | X      | X      | X      | X      |
| Lanyards                            | 3,140    | 3,140    | 3,140  | X      | X      | X      |
| Welcome Party Sponsorship           | Included | 5,890    | 5,890  | X      | X      | X      |
| Promotion at the snack area, 2 days | Included | Included | 1,180  | 1,180  | 1,180  | 1,180  |
| Agenda page ads                     | 470/ad   | 470/ad   | 470/ad | 470/ad | 470/ad | 470/ad |

### Notes

- Sponsorship prices are in USD, and the final sponsor fee will be converted using the exchange rate applied at payment time. The page uses 1 USD = 28 TWD as the reference example.
- Agenda page ads are available for all sponsorship levels, and the ad frequency depends on the sponsorship level.
- Booths are available only for Gold, Diamond, and Titanium sponsors.
- The sponsorship deadline is July 06, 2026.
- COSCUP does not provide attendee personal information to sponsors.
- If sponsorship benefits are not used within the year, they are considered relinquished and are non-refundable.

### Footnotes

- \*1: reception table
- \*2: logo on stage flag in keynote hall
- \*3: Welcome party sponsorship
- \*4: Welcome party free drink tickets
- \*5: Recruiting Board Sponsorship
- \*6: Promotion at the snack area
- \*7: Brand exposure on the conference table-front display

Refer to next page for additional sponsorship opportunities.

---

# Sponsorship packages

## Additional sponsorship opportunities

Additional sponsorship opportunities are available, including booth purchases, sponsored talks, workshops, stage flag branding, lanyards, Welcome Party sponsorship, snack area promotion, and agenda page ads.

If the standard sponsorship packages do not fit the sponsor's budget or goals, customized sponsorship arrangements may also be discussed.

If there are no sponsorship packages that fits your budget and needs, We're also open to discuss adjust existing package or designing package tailored for you.

Please contact us at [sponsorship@ubucon.asia](mailto:sponsorship@ubucon.asia) to discuss such opportunities!

---

<style scoped>
    section {
        background-image: url(https://assets.ubuntu.com/v1/ed94a429-0000_suru-corner-fan--top-right-light.jpg);
        background-position: top right;
        background-size: 20rem 15rem;
        align-content: end;
        font-size: 30px;
    }
    h1 {
        font-size: 60px;
    }
</style>

# End of Document

Thank you for consider sponsoring our event.
For inquires and securing sponsorship,
Contact sponsorship team at sponsorship@ubucon.asia

More details on this event can be found at
https://2026.ubucon.asia

<img src="./assets/2026/ntust.jpg" style="margin-left: -40px; margin-bottom: -50px; width: 210mm; height: 300px; object-fit: cover;">

<!-- _paginate: skip -->
<!-- footer: false -->
