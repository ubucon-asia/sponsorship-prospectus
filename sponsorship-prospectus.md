---
marp: true
theme: ubucon
paginate: true
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

![w:200](./assets/logo.svg)
# UbuCon Asia 2025
August 30 - 31
St. Xavier's College
Kathmandu, Nepal
**Sponsorship prospectus**

<img src="./assets/xsc.jpg" style="margin-left: -40px; margin-bottom: -50px; width: 210mm; height: 300px; object-fit: cover;">

<!-- _paginate: skip -->

---

<!-- header: ![w:50](./assets/logo.svg) -->
<!-- footer: https://2025.ubucon.asia | sponsorship@ubucon.asia -->

<img src="./assets/group_photo.jpg" style="margin-left: -40px; margin-top: -40px;  width: 210mm; height: 300px; object-fit: cover;">

# About UbuCon Asia

**UbuCon(s) (Ubuntu Conference)** are non-profit events organized by Ubuntu Communities worldwide. These events bring together hundreds of Open Source enthusiasts, users, developers, and contributors to share their stories and experiences regarding **Ubuntu** and relevant free and open source technologies for **servers, desktops, cloud computing, IoT, robotics, data science, AI/ML, and much more.**

In the spirit of promoting the love of Ubuntu and Open Source, **UbuCon Asia,** one of the regional UbuCon events **focusing specifically on the Asian region,** is organized annually by Ubuntu Communities and other free and open source communities across Asia. Following the success of previous editions in Seoul (South Korea), Surakarta (Indonesia), and Jaipur (India), we are pleased to announce that the 5th edition of UbuCon Asia will be hosted at **St. Xavier's College in Kathmandu, the cultural capital of Nepal.**

As a non-profit event organized by volunteers without compensation or stable funding, we rely on sponsorships to host these events. Such events enable community members to learn, share, and grow together while meeting many of their peers in person, sometimes for the first time.

## Event overview

- **Event name:** UbuCon Asia 2025
- **Dates:** August 30th - 31st
- **Venue:** St. Xavier's College, Kathmandu, Nepal
- **Participant scale:** Around 300 or more
- **Organizer:** UbuCon Asia Committee, GNOME Nepal

---

# The Ubuntu Project and Its Community

<!-- Text below are draft. You may improve it if you want -->
<div style="display: flex; flex-direction: row; margin-left: -40px; width: 210mm; height: 200px; ">
  <img src="./assets/uca22.JPG" style="flex: 1">
  <img src="./assets/uca23.JPG" style="flex: 1">
  <img src="./assets/uca24.jpg" style="flex: 1">
</div>

## Ubuntu

Ubuntu, co-developed by Ubunu Community with people from worldwide and Canonical, stands as the world's leading open source linux based operating system. With its mission to bring free software to the widest audience while accelerating innovation and underpinning operations, Ubuntu powers millions of devices from personal computers to cloud infrastructure, serving as the foundation for technological advancement in AI, cloud computing, IoT, and enterprise solutions.

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
    <img src="./assets/pashupatinath_temple.jpg" style="width: 100%; object-fit: cover;"> 
    <img src="./assets/ranipokhari.jpg" style="width: 100%; object-fit: cover;"> 
    </div>
  <div style="flex: 1; padding-left: 20px;">
    <h2>Nepal</h2>
    <p>TBD</p>
    <h2>Kathmandu</h2>
    <p>TBD</p>
  </div>
</div>
<hr/>
<div style="display: flex; flex-direction: row; align-items: flex-start;">
    <div style="flex: 1">
    <img src="./assets/xsc.jpg" style="width: 100%; object-fit: cover;">
    </div>
  <div style="flex: 1; padding-left: 20px;">
    <h2>St. Xavier's College (XSC)</h2>
    <p>TBD</p>
  </div>
</div>

---

# Who attends UbuCon Asia
<div style="display: flex; flex-direction: row;">
  <div style="flex: 1">
  <p><b>Software Engineers</b><br/>System, Application (Web, Desktop, etc), Embedded (IoT, Robotics, etc), Kernel & Operating Systems</p>
  <p><b>Academic & Other</b><br/>Students (IT related majors), Professors, Researchers, Analysts, Media, Marketing, Enterprisers</p>
  </div>
  <div style="flex: 1">
  <p><b>IT Infra & Operations</b><br/>SRE, SysAdmins, Solution Architects, DevOps, Cloud</p>
  <p><b>Data & AI</b><br/>Data Engineers, Data Scientists, DBA, AI/ML Engineers</p>
  <p><b>Community & Leadership</b><br/>Community Managers, DevRel, Technical Managers, OSPO Teams</p>
  </div>
</div>

## Highlights from last year
<div style="display: flex; flex-direction: row;">
  <p  style="flex: 1"><b>Total ~300</b><br>Participants</p>
  <p  style="flex: 1">Participants from <br><b>9 countries</b></p>
  <p  style="flex: 1">Session proposals<br><b>54 received</b></p>
  <p  style="flex: 1"><b>30 Speakers</b><br>in total</p>
</div>
<pre class="mermaid mermaid-100h">
pie showData
title Participants by profession (2024)
    "Students" : 50
    "Web Developer" : 60
    "DevOps Engineer" : 30
    "IoT Engineer" : 30

</pre>

---
# Become a sponsor!

---

# Past sponsors
<div class="imgrow">
  <img src="./assets/sponsor_logos/canonical.svg">
  <img src="./assets/sponsor_logos/onlyoffice.svg">
  <img src="./assets/sponsor_logos/fossunited.svg">
</div>
<div class="imgrow">
  <img src="./assets/sponsor_logos/naver_cloud.png">
  <img src="./assets/sponsor_logos/microsoft.png">
  <img src="./assets/sponsor_logos/invesume.png">
</div>
<div class="imgrow">
  <img src="./assets/sponsor_logos/whatap.png">
  <img src="./assets/sponsor_logos/nhncloud.png">
  <img src="./assets/sponsor_logos/nevacloud.png">
</div>
<div class="imgrow">
  <img src="./assets/sponsor_logos/biznet_giocloud.png">
  <img src="./assets/sponsor_logos/idnic.png">
  <img src="./assets/sponsor_logos/ahnlabcloudmate.svg">
</div>

---
<style scoped>
    table {
        font-size: 14px;
    }
</style>
# Sponsorship packages

| **Package** | Diamond | Gold | Silver | Bronze | Supporter  |
| --- | --- | --- | --- | --- | --- |
| **Slots** | 1 | 2 | 6 | ∞ | ∞ |
| Price(USD) | 10,000  | 6,000 | 3,500 | 1,600 | 500 - 800 |
| Price(NPR)<sup>*0</sup> | TBD  | TBD | TBD | TBD | TBD |
| **Logo exposures** || |
| Website | XL | L | M | S | S |
| Plenary banner<sup>*1</sup> | XL | L | M | S | XS |
| Stage (or Podium) banner | Yes | Yes | Yes | No | No |
| Nametag | Yes | Yes | No | No | No |
| Video banner<sup>*2</sup> | Yes | Yes | No | No | No |
| Video sponsor information scene<sup>*3</sup> | Yes | Yes | Yes | Yes | Yes |
| T-Shirt (or other swag if no T-shirt) | Yes | Yes | No | No | No |
| **Recognition** || |
| Recognition posting on social media | Yes | Yes | Yes | Yes | Yes |
| Recognition posting on blog | Yes | Yes | No | No | No |
| Mention during opening and closing session | Yes | Yes | Yes | Yes | Yes |
| **Engagements** || |
| Sponsored session<sup>*4</sup> | A Keynote<small>(30min)</small><br> + A Workshop<small>(90min)</small>,<br> A Talk<small>(30min)</small><br> or A BoF<small>(40-50min)</small> | A Talk<small>(30min)</small> or A Workshop<small>(90min)</small> | A Talk<small>(30min)</small> | A Lightning talk(5min) <small>(Limited FCFS)</small> | No |
| Sponsor booth | L | M | S<sup>*5</sup> | S<sup>*5</sup> <small>(500 USD Add-on FCFS)</small> | No |
| Promotion video during breaks | 3min | 2min | 1min | No | No |
| Distribute Promotional Material  | Handout on attendee check-in + At booth | Handout on attendee check-in + At booth | At booth | At booth <small>(If booth allocated)</small> | No |
| Promotional Email to all Attendees<sup>*5</sup> | Yes (One-time with custom content) | Yes (One-time with custom content) | Yes (One-time with custom content) | No | No |

Refer to next page for footnotes and additional sponsorship oppertunities.

---
# Sponsorship packages
## Footnotes

- *0: Price in Nepalese Rupees (NPR) is for business with primary office in Nepal.
- *1: A large size banner installed in reception area usually or enterance of the venue that number of attendees can take photo with banner as backdrop.
- *2: Banner of both live streams and video recordings if sessions will be streams or just on video recordings if not.
- *3: Duration of Scene will be around a few seconds in the video or live streams. 
- *4: Sponsored sessions are also subject to approval by the UbuCon Asia content team. Sponsors are required to share the Abstract alongside or before availing sponsorship for review. Note that session should be Ubuntu or relevant Open Source topics and need to comply with our Code of Conducts. Also, Sales or marketing pitches are not allowed.
- *5: Depending on logistics availability, this could be Booth with Size M but with located in less accessible area.
- *6: If sponsor desires, this could be replaced with "List of participants data with names, affiliation, job profession and email address". Only data from attendees opt-in to provide their data to sponsors during registration will be provided to sponsors. Attendees will be also informed about data provision to sponsors through registration form and also privacy policy if available.

## Additional sponsorship oppertunities

You may also become our in-kind sponsor by sponsoring coffee break, lunch, conference dinner, day trip, diversity initiatives and more! We’ll work with you to put together the right UbuCon Asia package for your company or organization. These additional opportunities may be sponsored separately or added on to a sponsorship package.

If there are no sponsorship packages that fits your budget and needs, We're also open to discuss adjust existing package or designing package tailored for you.

Please contact us at [sponsorship@ubucon.asia](mailto:sponsorship@ubucon.asia) to discuss such oppertunities! 

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
https://2025.ubucon.asia

<img src="./assets/xsc.jpg" style="margin-left: -40px; margin-bottom: -50px; width: 210mm; height: 300px; object-fit: cover;">

<!-- _paginate: skip -->
<!-- footer: false -->