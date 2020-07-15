---
layout: project
title: Science Intranet
descriptor: Uniting the Faculty of Science
abbr: sci-intranet
type: web
image: /assets/images/sci-intranet-thumb.jpg
client: Faculty of Science, University of Alberta
services: User Experience, Prototyping, Front End Development, Project Management
tools: Adobe Illustrator, Adobe Photoshop, Google Sites
team:
lingo: <dl>
    <dt>Faculty</dt>
    <dd>Capital <em>F</em>; Faculty of Science</dd>
    <dt>faculty</dt>
    <dd>Lowercase <em>f</em>; faculty member; professor</dd>
  </dl>
---
<div class="container">
  <div class="row">
    {% include proj-details.html %}
    <div class="col-sm">
      <h2><span class="numerals {{ page.type }}">00</span> Background</h2>
      <p>The Faculty of Science was looking for better ways to communicate with its departments and promote collaboration between the approximately <strong>300 faculty</strong> and <strong>700 support staff members</strong> in Science.</p>
      <h2><span class="numerals {{ page.type }}">01</span> Discovery</h2>
      <p>After having a discussion with the Dean about the difficulties he was facing and his vision for the project, we ran a few discovery pieces in tandem.</p>
      <h3>Working group</h3>
      <p>We assembled a working group made up of one faculty member and one staff member from each of the seven departments. Through our discovery sessions, we uncovered pain points and wish lists that we could address through the creation of a Science-specific internal portal.</p>
      <table class="table">
        <tbody>
          <tr>
            <th scope="row" style="width: 25%;">Clarity and transparency</th>
            <td>The mandate and contacts for some of the portfolios in the Dean's office was not always clear to department members; the departments weren't able to take full advantage of the skills and services offered by the Faculty</td>
          </tr>
          <tr>
            <th scope="row">Lack of continuity</th>
            <td>New Associate Deans are assigned to lead portfolios in the Dean's office every year or two; documents and important information was often sent out via email making it difficult for incoming ADs to build off of the work of their predessors; faculty and staff spend a lot of time searching their email for information</td>
          </tr>
          <tr>
            <th scope="row">Information overload</th>
            <td>Information about policies and procedures can come from many different sources making it difficult to discern what information is relevant and find a single source of truth; overflowing inboxes meant that some information might be missed</td>
          </tr>
          <tr>
            <th scope="row">Duplication of efforts</th>
            <td>Some departments had their own internal sites which they were also trying to keep current; some of this information should be owned and updated by the Faculty of Science</td>
          </tr>
          <tr>
            <th scope="row">Optimize external sites</th>
            <td>In some instances, information internal to unit administration was being housed on the external site (aimed at students and visitors); this causes confusion, complicates  already deep navigation, and degrades SEO</td>
          </tr>
        </tbody>
      </table>
      <h3>Content survey</h3>
      <p>A content survey was sent out to all prospective users of the internal Science site. We used the 135 responses to help prioritize features, shape the content and inform the design.</p>
      <div class="container callout">
        <div class="row">
          <div class="col"><img src="/assets/images/sci-intranet-surveys.png" alt="Science Intranet content survey" /></div>
        </div>
      </div>
      <h3>Content owner consultations</h3>
      <p>I met with the content owners for each of the portfolios about the types of content they wanted to share. This shaped the site structure and got us thinking about how the content could be presented and maintained.</p>
      <h2><span class="numerals {{ page.type }}">02</span> Ideation + Design</h2>
      <h3>Platform selection</h3>
      <p>After evaluating a number of different platform options, and talking to the Faculty of Arts (a unit similar to Science in size and diversity) about their internal portal, a customized Google Site came out on top. The University of Alberta is a Google campus&mdash;so being able to leverage many of the Google's integrated features was a big selling point. These included</p>
      <ul>
        <li>Central authentication (already built-in)</li>
        <li>File storage and integration of Google Drive, Calendar, Sheets and more</li>
        <li>Automatic audit trail, versioning/history, and rollback</li>
        <li>Familiar set of tools for faculty and staff members to use</li>
      </ul>
      <h3>Interface design</h3>
      <p>From there, I put together wireframes and ran some 1-on-1 prototype testing with individual volunteers to check assumptions and validate the design.</p>
      <div class="container callout">
        <div class="row">
          <div class="col"><img src="/assets/images/sci-intranet-wires.png" alt="Science Intranet wireframes" /></div>
        </div>
      </div>

      <h2><span class="numerals {{ page.type }}">03</span> Solution</h2>
      <p>Aligned with the institutional look and feel, the <em>Science Intranet</em> provides a simple way for multiple contributors in the Dean's office to disseminate content while giving members of Science a central source for administrative procedures, documents and contacts.</p>
      <br />
      <table class="table callout">
        <tbody>
          <tr>
            <td class="display-2">1</td>
            <td class="lead">Central source of information</td>
            <td>
              <ul>
                <li>Faculty portfolio owners filter and present information relevant to Science linking to other University units where applicable</li>
                <li>Departments would no longer have to maintain Faculty level information on their own sites</li>
              </ul>
            </td>
          </tr>
          <tr>
            <td class="display-2">6</td>
            <td class="lead">Portfolios brought to the forefront</td>
            <td>
              <ul>
                <li>Each portfolio in the Dean's office was given its own section on the <em>Science Intranet</em> to provide continuity and a home for documents, procedures and updates</li>
                <li>A section at the top of the page (highlighted in green) was reserved for a concise definition of the portfolio's mandate</li>
              </ul>
            </td>
          </tr>
          <tr>
            <td class="display-2">1</td>
            <td class="lead">Contact list to rule them all</td>
            <td>
              <ul>
                <li>Updating the master contact list (in Google Sheets) would push the changes to the contact area on each page of the site via Google Script</li>
                <li>This list powered a searchable and sortable Science directory</li>
                <li>Contact lists by department with the most up-to-date information could be generated as a PDF file to share with units outside of Science</li>
              </ul>
            </td>
          </tr>
          <tr>
            <td class="display-2">8</td>
            <td class="lead">Integrated event calendars</td>
            <td>
              <ul>
                <li>Fed each of the departmental calendars plus the Science event calendar into an integrated Google calendar to raise awareness of open events happening in other departments</li>
                <li>Makes it easy to copy events to your own calendar or subscribe to a feed</li>
              </ul>
            </td>
          </tr>
          <tr>
            <td class="display-2">1</td>
            <td class="lead">Easy to maintain system</td>
            <td>
              <ul>
                <li>Took advantage of systems (ie. calendars and document folders) already being maintained by the content creators as to not create additional work</li>
                <li>Document lists could be updated on the site by simply adding or removing items from a specific shared Google Drive folder</li>
                <li>Some specialty (searchable, sortable, filterable) tables were created with the ability to be updated by changing a Google Sheet</li>
              </ul>
            </td>
          </tr>
        </tbody>
      </table>
      <br />
    </div>
  </div>
  <div class="row portfolio">
    <div class="col">
      <img src="/assets/images/sci-intranet-home.jpg" style="width: 100%">
    </div>
  </div>
</div>
