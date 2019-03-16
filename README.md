# DC Speaking Proposals

Do you want to speak at a DC meetup? How about find a speaker for your meetup? You're in the right place!

There are a lot of talks that would be awesome for multiple meetups in DC, and it's difficult to pitch to all of them at once right now. Organizers are always looking for speakers. This repository bridges that gap by allowing speakers to pitch their talks to a bunch of meetups all at once.

## Speakers

Please [fill out an issue](https://github.com/dctech/speaking/issues/new?template=talk.md) with information about your proposed talk. There's a template with some questions to answer about your talk within that issue. Feel free to skip any you don't feel comfortable answering. Also, add labels to the issue so your talk is easier to find.

## Organizers

Reach out to the speakers whose talks interest you! See also: [talks grouped by author](https://dctech.github.io/speaking/).

## Community

Feel free to suggest a talk your meetup would like to hear! To request a talk idea, please [fill out an issue](https://github.com/dctech/speaking/issues/new?template=request.md) with the information about the talk you'd like to hear.

### Participating Meetups

- [ACM Washington DC](https://www.meetup.com/ACM-DC/)
- [Arlington Ruby](https://www.meetup.com/Arlington-Ruby/)
- [Art + Code Collective](https://www.meetup.com/Art-Code-Collective/members/?sort=join_date&desc=true)
- [Black Code Collective](https://www.meetup.com/Black-Code-Collective/)
- [DevOpsDC](https://www.meetup.com/DevOpsDC) (we also publish our [speaker pipeline](https://github.com/devopsdc/devopsdc/projects/1))
- [DC Hack && Tell](https://dc.hackandtell.org/)
- [DC JavaScript](https://www.meetup.com/DC-JavaScript/)
- [DC Python](https://www.meetup.com/DCPython/)
- [DC Ruby Users Group](https://www.meetup.com/dcruby/)
- [DC VueVixens](https://www.meetup.com/VueVixens-DC/)
- [Django District](https://www.meetup.com/Django-District/)
- [ForeFront](https://4front.io/)
- [.NET DC User Group](https://www.meetup.com/dotnetdc/)
- [Node.DC](https://www.meetup.com/node-dc/)
- [NoVa DevOps](https://www.meetup.com/nova-devops/)
- [NOVA Kubernetes](https://www.meetup.com/NOVA-Kubernetes/)
- [NoVaJS](https://www.meetup.com/NoVaJS/)
- [Papers We Love DC/NoVA](https://www.meetup.com/Papers-We-Love-DC-NoVA/)
- [ReactMD](https://www.meetup.com/React-MD/)
- [RVA.js](https://www.meetup.com/rva-js/)
- [TechTalkDC](https://www.meetup.com/techtalkDC/)
- [The Joy of Programming](https://www.meetup.com/Joy-of-Programming-DC/)
- [VueDC](https://www.meetup.com/vue-dc/)
- [Women Who Code DC](https://www.meetup.com/Women-Who-Code-DC/)
- [DC Women in Agile](https://www.meetup.com/Women-in-Agile-DC-Metro/)

### About the Repo

This is a joint project by some DC Tech organizers. If you have an idea for improving the repo or want your meetup group to participate, feel free to submit a pull request or leave an issue with the `meta` label!

#### Intent
From a speaker's perspective, it is great to be able to submit talks to many groups at once. This particularly affects talks that are general or evergreen, like those that are focused on soft skills and blogging -- these apply to many different audiences, not just a particular language or interest group.

From an organizer's perspective, it is great to have a list of folks available to fill gaps in speaking schedules. Often gaps are filled by tapping into an in-network (“oh, I know this person has a talk they can whip up!“), but that furthers in-network biases. This repo helps reduce that in-network bias some amount.

#### Technical Setup
Meetup group admins (or anyone) can get notified about potential talks by "watching" the repo (next to "star" and "fork").

To help people fill out talk-submission and talk-request issues in a consistent way, we use [GitHub Issue Templates](https://help.github.com/articles/about-issue-and-pull-request-templates/).

We also have two Probot scripts that auto-respond to issues for us. We use the [Auto-comment Probot](https://probot.github.io/apps/auto-comment/) to welcome people who submit a talk-issue. We use the [Stale Probot](https://probot.github.io/apps/stale/) to close talk-issues that are very old and not recently touched.

You can see the config for each of these in our [.github](https://github.com/dctech/speaking/tree/master/.github) folder.
