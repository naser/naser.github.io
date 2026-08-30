---
layout: page
title: Contact
share-title: Contact | THREADS Lab (Naser Ezzati-Jivan)
share-description: Contact THREADS Lab at Brock University about graduate and undergraduate research positions, collaboration, or publications.
keywords: "THREADS Lab, Naser Ezzati-Jivan, Brock University, prospective students, PhD positions, MSc positions, undergraduate research, research collaboration, graduate supervision"
---

### Prospective students

**We are always looking for talented PhD, MSc, and undergraduate students.**

If you work on — or want to work on — software observability and execution tracing, software performance engineering, debugging and root-cause analysis, distributed and heterogeneous systems, trustworthy and agentic AI, or energy-aware and embodied AI systems, we would like to hear from you.

Generic messages are easy to spot and rarely get a reply. A good message is short, specific, and shows you have read something we have actually written. Please include:

1. **Who you are** — your background, degree program, and current or most recent institution.
2. **Why THREADS Lab** — which of our [research directions]({{ site.baseurl }}/tabs/research/) interests you, and *why* that problem interests you. Referring to a specific paper from our [publication catalog]({{ site.baseurl }}/research-publications/) is the clearest way to show this.
3. **How you could contribute** — the skills and experience you would bring (for example systems programming, tracing and profiling tools, Linux internals, distributed systems, machine learning, LLMs, data analysis), and what you would want to build or investigate.
4. **What you are looking for** — PhD, MSc, undergraduate project, internship, or visiting position, and your intended start date.
5. **Your CV**, and transcripts if you have them.

Applicants to graduate programs must also apply formally through [Brock University graduate admissions](https://brocku.ca/graduate-studies/) — contacting us directly does not replace that application.

### Collaboration and other inquiries

We welcome inquiries from postdoctoral researchers, visiting researchers, industry partners, and academic collaborators working on aligned problems.

### Send a structured enquiry

Choose what describes you and fill in the fields. This composes a well-organised email in your own mail program, addressed to Naser Ezzati-Jivan — nothing is submitted to any third-party service, and you can review or edit the message before sending it.

<div class="enquiry" markdown="0">
  <div class="enquiry-tabs" role="tablist" aria-label="Type of enquiry">
    <button type="button" class="enquiry-tab" role="tab" data-panel="student" aria-selected="true">Prospective student</button>
    <button type="button" class="enquiry-tab" role="tab" data-panel="industry" aria-selected="false">Industry</button>
    <button type="button" class="enquiry-tab" role="tab" data-panel="academic" aria-selected="false">Academic collaborator</button>
  </div>

  <form id="enquiry-form" novalidate>
    <div class="enquiry-field">
      <label for="eq-name">Your name</label>
      <input type="text" id="eq-name" name="name" autocomplete="name">
    </div>
    <div class="enquiry-field">
      <label for="eq-email">Your email</label>
      <input type="email" id="eq-email" name="email" autocomplete="email">
    </div>

    <!-- Prospective student -->
    <div class="enquiry-panel" data-panel="student">
      <div class="enquiry-field">
        <label for="eq-level">Position you are interested in</label>
        <select id="eq-level" name="level">
          <option>PhD</option>
          <option>MSc</option>
          <option>Undergraduate project (3P99)</option>
          <option>Undergraduate honours thesis (4F90)</option>
          <option>International internship (e.g. Mitacs Globalink)</option>
          <option>Postdoctoral researcher</option>
        </select>
      </div>
      <div class="enquiry-field">
        <label for="eq-start">Intended start</label>
        <input type="text" id="eq-start" name="start" placeholder="e.g. September 2027">
      </div>
      <div class="enquiry-field">
        <label for="eq-background">Your background
          <span class="hint">Degree, institution, and relevant skills — systems, tracing, distributed systems, ML, and so on.</span>
        </label>
        <textarea id="eq-background" name="background"></textarea>
      </div>
      <div class="enquiry-field">
        <label for="eq-direction">Which research direction interests you, and why?
          <span class="hint">Referring to a specific paper or project is the clearest way to show you have read our work.</span>
        </label>
        <textarea id="eq-direction" name="direction"></textarea>
      </div>
      <div class="enquiry-field">
        <label for="eq-contribute">What would you bring, or want to build?</label>
        <textarea id="eq-contribute" name="contribute"></textarea>
      </div>
      <div class="enquiry-field">
        <label for="eq-cv">Link to your CV
          <span class="hint">A link is easier than an attachment. You can attach files in your mail program before sending.</span>
        </label>
        <input type="text" id="eq-cv" name="cv">
      </div>
    </div>

    <!-- Industry -->
    <div class="enquiry-panel" data-panel="industry" hidden>
      <div class="enquiry-field">
        <label for="eq-org">Organisation and your role</label>
        <input type="text" id="eq-org" name="org">
      </div>
      <div class="enquiry-field">
        <label for="eq-area">Problem area</label>
        <select id="eq-area" name="area">
          <option>Software observability and tracing</option>
          <option>Performance engineering and reliability</option>
          <option>AI, LLMs, and agentic systems</option>
          <option>Physical and embodied AI</option>
          <option>Something else</option>
        </select>
      </div>
      <div class="enquiry-field">
        <label for="eq-problem">The problem you would like to work on
          <span class="hint">What behaviour can you not currently explain or measure?</span>
        </label>
        <textarea id="eq-problem" name="problem"></textarea>
      </div>
      <div class="enquiry-field">
        <label for="eq-mode">Collaboration you have in mind</label>
        <select id="eq-mode" name="mode">
          <option>Funded intern or student on the problem (e.g. Mitacs)</option>
          <option>Joint grant application</option>
          <option>Focused evaluation of an existing system</option>
          <option>Exploratory conversation first</option>
        </select>
      </div>
      <div class="enquiry-field">
        <label for="eq-timeline">Timeline</label>
        <input type="text" id="eq-timeline" name="timeline" placeholder="e.g. starting next term, or flexible">
      </div>
    </div>

    <!-- Academic collaborator -->
    <div class="enquiry-panel" data-panel="academic" hidden>
      <div class="enquiry-field">
        <label for="eq-inst">Institution and position</label>
        <input type="text" id="eq-inst" name="institution">
      </div>
      <div class="enquiry-field">
        <label for="eq-kind">Type of collaboration</label>
        <select id="eq-kind" name="kind">
          <option>Joint grant application</option>
          <option>Co-supervision of a student</option>
          <option>Visiting researcher or scholarly visit</option>
          <option>Joint paper or shared artifact</option>
          <option>Workshop, tutorial, or special issue</option>
          <option>Something else</option>
        </select>
      </div>
      <div class="enquiry-field">
        <label for="eq-topic">Research overlap
          <span class="hint">Where do your interests meet ours?</span>
        </label>
        <textarea id="eq-topic" name="topic"></textarea>
      </div>
      <div class="enquiry-field">
        <label for="eq-profile">Link to your profile or group page</label>
        <input type="text" id="eq-profile" name="profile">
      </div>
    </div>

    <div class="enquiry-field">
      <label for="eq-notes">Anything else</label>
      <textarea id="eq-notes" name="notes"></textarea>
    </div>

    <div class="enquiry-actions">
      <button type="submit" class="enquiry-submit">Compose email</button>
      <span class="enquiry-note" style="margin:0">Opens in your mail program</span>
    </div>
    <p class="enquiry-error" id="enquiry-error">Please add your name and email before composing the message.</p>
  </form>

  <p class="enquiry-note">If the button does not open your mail program — some webmail setups do not register as the default handler — just email <a href="mailto:nezzati@brocku.ca">nezzati@brocku.ca</a> directly, covering the same points.</p>
</div>

<script>
(function () {
  var form = document.getElementById('enquiry-form');
  if (!form) return;
  var tabs = document.querySelectorAll('.enquiry-tab');
  var panels = document.querySelectorAll('.enquiry-panel');
  var error = document.getElementById('enquiry-error');
  var active = 'student';

  function select(name) {
    active = name;
    tabs.forEach(function (t) { t.setAttribute('aria-selected', String(t.dataset.panel === name)); });
    panels.forEach(function (p) { p.hidden = (p.dataset.panel !== name); });
  }
  tabs.forEach(function (t) {
    t.addEventListener('click', function () { select(t.dataset.panel); });
  });

  function val(id) {
    var el = document.getElementById(id);
    return el && el.value ? el.value.trim() : '';
  }
  function line(label, value) {
    return value ? label + ':\n' + value + '\n\n' : '';
  }

  form.addEventListener('submit', function (e) {
    e.preventDefault();
    var name = val('eq-name');
    var email = val('eq-email');
    if (!name || !email) { error.style.display = 'block'; return; }
    error.style.display = 'none';

    var subject, body = '';
    body += line('Name', name) + line('Email', email);

    if (active === 'student') {
      subject = 'Prospective student enquiry — ' + val('eq-level') + ' — ' + name;
      body += line('Position of interest', val('eq-level'));
      body += line('Intended start', val('eq-start'));
      body += line('Background', val('eq-background'));
      body += line('Research direction of interest, and why', val('eq-direction'));
      body += line('What I would bring', val('eq-contribute'));
      body += line('CV', val('eq-cv'));
    } else if (active === 'industry') {
      subject = 'Industry collaboration enquiry — ' + val('eq-org');
      body += line('Organisation and role', val('eq-org'));
      body += line('Problem area', val('eq-area'));
      body += line('Problem', val('eq-problem'));
      body += line('Collaboration type', val('eq-mode'));
      body += line('Timeline', val('eq-timeline'));
    } else {
      subject = 'Academic collaboration enquiry — ' + val('eq-inst');
      body += line('Institution and position', val('eq-inst'));
      body += line('Type of collaboration', val('eq-kind'));
      body += line('Research overlap', val('eq-topic'));
      body += line('Profile', val('eq-profile'));
    }
    body += line('Additional notes', val('eq-notes'));
    body += '\n— Sent via the THREADS Lab contact form';

    window.location.href = 'mailto:nezzati@brocku.ca'
      + '?subject=' + encodeURIComponent(subject)
      + '&body=' + encodeURIComponent(body);
  });
})();
</script>

### Contact details

**Naser Ezzati-Jivan**\
Associate Professor, Department of Computer Science\
*Office*: MC J312\
Brock University, St. Catharines, Ontario\
905 688 5550 ext 3520\
nezzati@brocku.ca

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2912.2821974015033!2d-79.2481545!3d43.1195977!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89d34e32c65ca64b%3A0xb37a58fc7fae51e8!2sMackenzie%20Chown%20Complex%2C%20St.%20Catharines%2C%20ON%20L2S%203A1!5e0!3m2!1sen!2sca!4v1660455206827!5m2!1sen!2sca" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

**Profiles and publications:** [Research]({{ site.baseurl }}/tabs/research/) · [People]({{ site.baseurl }}/tabs/people/) · [Google Scholar](https://scholar.google.ca/citations?hl=en&user=sJWcLv8AAAAJ&view_op=list_works&sortby=pubdate) · [ORCID](https://orcid.org/0000-0003-1435-6297) · [LinkedIn](https://www.linkedin.com/in/naser-ezzati-jivan-71418724) · [Publication catalog]({{ site.baseurl }}/research-publications/)
