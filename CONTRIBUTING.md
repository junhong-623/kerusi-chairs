# Share a chair

Use the [chair submission form](https://github.com/junhong-623/kerusi-chairs/issues/new?template=chair-submission.yml).
You need a GitHub account to submit. Opening an issue is enough; you do not need
to edit website code or make a pull request.

## Model

Export one self-contained **GLB** file with its textures embedded. The chair
should have a complete back and underside: visitors can turn it in every
direction. Use a sensible scale, keep it upright, and remove cameras, lights,
backgrounds, floors and unrelated scene objects before export.

Keep the GLB at or below **10 MB**, preferably below **5 MB**. Aim for fewer than
100,000 triangles and textures no larger than 2048 × 2048 pixels for a responsive
mobile preview. These geometry and texture values are review targets, not
automatic upload validation.

For this first version, submit a static chair with standard glTF materials.
Avoid animations and custom rendering extensions. The maintainer will check
actual browser compatibility before accepting it.

### File limits

| File | Requirement |
| --- | --- |
| Submitted GLB | At most **10 MB**, preferably under **5 MB**. |
| Preview or share image | PNG, JPEG or WebP; at most **3 MB** each. A dedicated share image is optional; **1200 × 630** is recommended. |
| ZIP package | Apply the model limit to each extracted GLB. Include the model, previews and permission notes; the backend does not extract ZIPs automatically. |

The admin backend's **12 MB** model upload ceiling is a technical allowance,
not the contribution limit. Submissions still follow the **10 MB** requirement.
Backend byte limits use 1024 × 1024 bytes for each MB displayed in its interface.
The form requires filled fields; maintainers check file sizes and permissions.

Paste a public model download link in the form, or attach a ZIP containing the
GLB. GitHub's file attachments do not directly accept GLB, so ZIP is the upload
route. Include a screenshot or render in the preview field. The form supports
attachments in its text areas.

For automatic import, a GitHub-hosted download URL whose path ends in `.glb`
and a GitHub-hosted image URL ending in `.png`, `.jpg`, `.jpeg` or `.webp` are
currently easiest to recognise. A GitHub file page is not a direct model
download; use its raw/download link. ZIPs, other file hosts and attachment URLs
that the importer cannot recognise are reviewed and uploaded manually by the
maintainer. These submissions are welcome too; allow time for that extra step lah.

## Story and creator credit

Supply your chair's name, a short description, and your preferred creator name.
A public portfolio link is optional. Write in English, Bahasa Melayu or Chinese;
you do not need to translate all three yourself. The maintainer prepares the
other languages and can ask you to check the wording.

Keep personal contact information out of the issue. We can ask follow-up
questions through GitHub comments.

If you already have all three names, write them as `中文名称 · English name ·
Nama Bahasa Melayu`. Three-language stories can use separate **中文**,
**English** and **Bahasa Melayu** headings. This is optional; one language is
still enough. See [Kenduri Red / 庙会红椅](https://github.com/junhong-623/kerusi-chairs/issues/1)
for a complete example of model links, renders, stories and permission.

## Permission

Identify the license for the model and all embedded textures, with their source
links and required credits. Do not submit a model copied from a shop or asset
library unless its license actually allows this use.

If you created every asset and choose to give project-specific permission,
include a statement such as:

> I created this model and its textures. I allow keru.si to display them, host
> and distribute them as website assets, and optimise the files for web viewing,
> while displaying my creator credit.

This statement is a submission option, not a license automatically applied to
every asset. The maintainer reviews your actual permission and any restrictions.
Submitting an issue does not transfer ownership of your work.

## What happens next

1. The owner checks the file, story and permission and replies in your issue.
2. If changes are needed, you can update the download link or attachment.
3. The owner imports a private draft through the website admin, or downloads
   and uploads the files manually. The owner checks the three languages,
   author and permission, then saves and tests the 3D preview.
4. The owner explicitly publishes the reviewed draft. Only the published
   snapshot appears in the exhibition, with its own `/chairs/<chair-id>` link.
5. Once that public result is verified, the owner replies with the link, marks
   the GitHub issue `published` and closes it. GitHub labels and replies are
   managed manually; the admin does not update them automatically.

Files are reviewed manually. A submission does not execute code, change the
website, or trigger deployment.
