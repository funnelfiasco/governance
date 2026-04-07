# GUAC Maintainers Meeting: 2026-04-06

Recording: https://youtu.be/TLOp-B0a7S4

## Attendees

| Name | Email | Affiliation | Pronouns
| ---- | ----- | ----------- | --------
| Ruben Romero Montes | rromerom@redhat.com | Red Hat | he/him
| Gagan H R | ghr@guidewire.com | Guidewire | he/him
| Ben Cotton | ben@kusari.dev | Kusari | he/him
| Justin Cappos | jcappos@nyu.edu | NYU | he/him
| Michael Lieberman | mike@kusari.dev | Kusari | he/him
| Victor Lu

## Agenda/notes

* [Victor] Transparency Exchange API
    * Already has SPDX support built-in
        * https://spdx.org/rdf/3.1/spdx-model.ttl
    * Is it worth discussing?
        * Mike: yes, add an issue. It would be cool to have a collector to grab SBOMs automatically. GUAC is more focused on consumption, so we’d be interested in knowing who is currently distributing these SBOMs so we can go test it out.
    * Mike: GUAC’s SPDX 3 support is blocked on implementation of an upstream Go library (https://github.com/spdx/tools-golang/issues/237)
* [Gagan] PRs need review:
    * https://github.com/guacsec/guac/pull/2935
    * https://github.com/guacsec/guac/pull/2931
    * https://github.com/guacsec/guac/pull/2916
* [Mike] CNCF created Seebom: https://seebom.cncf.io/
