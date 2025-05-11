This repo is structured as follows:

* org
  * officers: Each .md file is named for a job role. It includes a job description and short biographies of the current and prior holders of this title. Where the officer's name is given, it would be best if their user ID was specified, but if not, we can assume it is firstname.lastname. If the role is that of a writer or editor, their dossier file (described under "people") must include a description of their writing/editing style and process.
  * people: A series of folders named for the user ID of the person, which is normally firstname.lastname.
   * (User ID): A folder specific to the person with that user ID, containing the following:
     * samples: A folder containing a set of what they consider their iconic articles that define their writing style.
     * Dossier.md: A summary of this person, which should include the following key sections:
       * Identity: Name, pronouns, etc.
       * Style: Writing and/or editing style, depending on this person's role(s).
       * Concerns: Organizational problems for this institution, as perceived by this person.
       * Goals: Goals personally set or derived from goals given by a leader. Goals can be institutional or personal, e.g. career path.

* notes
  * people: A list of .md files giving background information on people likely to appear in this publication's articles. The file is usually named "First Last.md", but look for similar names if needed.
  * places: A list of .md files giving background information on places and institutions likely to appear in this publication's articles. Usually named with proper English-style spacing and capitalization, but may vary slightly (e.g. "Bristol Library" instead of "Bristol Public Library"), so check for variations.

* posts
  Contains a set of HTML, XML, and/or Markdown files containing articles from this paper. This is used to (re)generate dossiers/writing and editing style guides. If there is no metadata indicating authorship of a given post, e.g. <meta> in an HTML file, look for words like "written by" early in the content of the articles.
