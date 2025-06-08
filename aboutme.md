---
layout: default
title: About Us
---

<div class="about-container">
  <!-- <p class="team-head-text stylish-heading">About Us</p> -->

  <section class="about-section">
    <h2 class="section-heading">The Project Management Club at DBS</h2>
    <p>
      The Project Management Club at DBS aims to inspire and equip students with practical and professional project management knowledge. It provides a dynamic platform for learning, leadership, networking, and collaboration through PMI’s resources and guidance. Our club supports students in applying project management principles effectively in both personal and professional contexts.
    </p>
  </section>

  <section class="about-section">
    <h2 class="section-heading">Mission Alignment</h2>
    <p>
      Our club is deeply aligned with the mission and vision of the Project Management Institute (PMI):
    </p>
    <ul>
      <li><strong>Mission:</strong> Provide project professionals and employers with resources, continuous development, and globally recognized certifications.</li>
      <li><strong>Vision:</strong> Advance a world where every project delivers maximum value, responsibly.</li>
    </ul>
  </section>

  <section class="about-section">
    <h2 class="section-heading">Core Values and Practices of PMI</h2>
    <p>
      We embrace and embody PMI's core values in all our activities and culture:
    </p>

    <div class="grid" role="list">
      <article class="card" role="listitem">
        <ul>
          <li><strong>Make It Easy</strong> – Reduce complexity and foster access to knowledge.</li>
          <li><strong>Aim Higher</strong> – Strive for excellence and accountability.</li>
          <li><strong>Be Welcoming</strong> – Foster diversity, inclusivity, and respect.</li>
        </ul>
      </article>
      <article class="card" role="listitem">
        <ul>
          <li><strong>Embrace Curiosity</strong> – Encourage learning and innovation.</li>
          <li><strong>Together We Can</strong> – Promote collaboration and shared purpose.</li>
        </ul>
      </article>
    </div>
  </section>
</div>

<style>
  .about-container {
    max-width: 1200px;
    margin: 3rem auto;
    padding: 0 1rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }

  .stylish-heading {
    text-align: center;
    font-size: 2.8rem;
    font-weight: 700;
    color: #222;
    margin-bottom: 2rem;
    letter-spacing: 0.05em;
  }

  .about-section {
    background: white;
    border-radius: 16px;
    box-shadow: 0 8px 20px rgba(25, 45, 90, 0.1);
    padding: 2.5rem 2.5rem;
    margin-bottom: 2.5rem;
  }

  .section-heading {
    font-size: 1.8rem;
    font-weight: 700;
    color: #163172;
    margin-bottom: 1.2rem;
  }

  p {
    font-size: 1.15rem;
    color: #333758;
    margin-bottom: 1.5rem;
    line-height: 1.7;
  }

  ul {
    padding-left: 1.4rem;
    color: #2a2a4d;
  }

  ul li {
    margin-bottom: 0.9rem;
    font-size: 1.05rem;
  }

  ul li strong {
    color: #163172;
  }

  .grid {
    display: flex;
    gap: 2rem;
    flex-wrap: wrap;
    margin-top: 2rem;
  }

  .card {
    flex: 1;
    min-width: 280px;
    background: #e5ebff;
    padding: 1.8rem 2rem;
    border-radius: 12px;
    box-shadow: 0 6px 15px rgba(22, 49, 114, 0.12);
  }

  @media (max-width: 700px) {
    .grid {
      flex-direction: column;
    }
  }
</style>
