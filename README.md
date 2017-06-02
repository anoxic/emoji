emoji
=====

an issue / task track. i'm playing with symfony for this.
💥

## data structures (planned)

minimum:

* user (id, login, pass)
* org (id, name)
* task (id, parent, summary, description, open, priority (low, normal, high), type (bug, story, task), status (to do, in progress, review, done, stagnant))
* segment (id, org, name (e.g. project/client/sprint/version))
* slug (id, preferred (bool), slug, user, org, task, segment) - for "public ids" for various things
* search (elastic)

later possibly:

* "customizable bits"? add to org, on backend allow list str, on update, if  used by one org, change details, else new
    * type (id, slug, name)
    * status (id, slug, name)
* assignment
* comments
* attachments
* notifications
* integrations (mainly for version control and deployment)
* automatic email assignment / email management
* due dates
* logging (keep track of all dem changes)
* permissions (who cares for now)
* "fastpage" features
* wiki-like thing
* billing

