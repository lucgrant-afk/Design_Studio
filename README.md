# Design Studio · DP Design Technology

An independent classroom teaching interface for the supplied first-assessment-2027 curriculum.

## Use

Open the hosted site. Select a topic, then Explore, Activities, Exam practice, Glossary or Syllabus checklist. Present enlarges the lesson and hides navigation. Escape exits presentation mode. Activities include a classroom timer. Your responses and reviewed checkboxes save in this browser; export and import them through Coverage & audit.

Includes 24 topics, 161 numbered understandings, 129 preserved activity cards, 24 new classroom challenges, 10 virtual labs, 351 official topic-glossary entries plus original teaching explanations. Original incomplete questions are labelled and supplied with repaired replacements. The repaired modulus quiz appears once as interactive practice.

## GitHub Pages

Extract `design-studio-github-pages.zip`. Upload its contents (index.html, CSS, JS, JSON and image) to the root of your chosen repository. In Settings → Pages choose Deploy from a branch, choose the branch and /(root), then Save. No build or API key is required. GitHub account/plan rules determine available repository visibility and hosting options.

## Local preview

Run `python3 -m http.server 8000 --directory dist` from this source checkout and open http://localhost:8000. In the downloadable Pages package, run the command without `--directory dist` from the extracted folder. Opening index.html directly from a file URL cannot load JSON in many browsers.

## Content and limitations

Source: user-supplied teaching HTML, Design technology guide (first assessment 2027), and topic-specific glossary. Syllabus hours are topic allocations, not a complete course timetable. Syllabus navigation suggestions are keyword matches, not verified one-to-one teaching alignment. This is not an official IB resource. See the included curriculum audit for targeted findings and repairs.

Virtual lab data are illustrative; assumptions and units appear in each lab. No AI marking or student account service is used. External images, animated media and videos from the original lessons depend on third-party availability and school filtering. Broken images fall back to an original-resource link. The hero is an AI-generated conceptual still life; card and lab diagrams are authored schematics.
