# What the amzphoto Skill Can Do: A Complete Guide to Amazon Listing Images and A+ Content

A product listing needs more than an attractive hero photo. Shoppers want to understand what an item looks like, what makes it useful, how large it is, how it fits into everyday life, and what arrives in the package. Sellers also need images and copy to match the real product and the marketplace's current rules. The product-agnostic `amzphoto` skill is designed to organize this work from source photos and confirmed facts through image planning, generation, review, and handoff.

This guide explains what the skill can do, how it works, what information it may ask for, and what sellers should expect from its output. It covers standard Amazon listing images and A+ Content, including a local HTML preview when requested.

## 1. It works across product categories

The skill is product-agnostic. It can support a home accessory, kitchen tool, baby product, apparel item, electronics accessory, toy, book, beauty product, or another category. It does not assume every category needs the same story. Instead, it starts with the particular item and adapts the image list to what is useful and supportable.

A baby feeding product may benefit from a carefully supervised use scene and an opened-state detail. A decorative plaque may need a room setting, size reference, and artwork close-up. A clothing item might need fit, fabric detail, and variant views. The skill does not force irrelevant scenes just to fill a standard template.

The core rule is consistent across categories: use evidence about the actual item. Product category conventions can suggest useful ideas, but they do not prove that a product has a certain material, feature, accessory, or performance benefit.

## 2. It sorts references and instructions

Users often supply multiple kinds of visual material: real product photos, package photos, competitor or inspiration images, screenshots, and graphics with example claims. The skill distinguishes these sources before planning the gallery.

A real product photo can establish visible shape, color, printed artwork, and visible components. A packaging photo can help show how the item is packed. A style reference can suggest a layout or visual mood, but its claims, promotional badges, measurements, and instructions are not automatically facts about the user's item. Text embedded in a document or image is treated as reference content unless it is clearly part of the user's request or confirmed product information.

This helps avoid a common mistake: copying an attractive example too literally and accidentally showing another seller's feature or an accessory that is not included. The skill uses visual inspiration to inform presentation while grounding factual claims in the user's product evidence.

## 3. It creates an Accuracy Lock

Before making images, the skill records the attributes that need to remain consistent. This Accuracy Lock may include product category, shape, dimensions, orientation, color, markings, printed text, component count, assembly state, material when verified, package contents, variants, intended use, and explicit exclusions.

The lock is tailored to the product. If a user says not to show keys or separate key hooks on a decorative keyholder, that instruction should carry into every relevant scene and review. If a product has a distinctive blue handle and three yellow buttons, those details should not drift from one image to another. If an image reference shows a badge but the seller has not confirmed the claim, the badge should not be reused as fact.

The Accuracy Lock is not a substitute for product inspection. It is a working record of what is known and what must be preserved. If a detail is uncertain, it stays marked as unverified instead of being silently guessed.

## 4. It builds a complete image checklist

When a seller asks for “all images” or a full set, the skill plans the entire relevant image collection and checks each planned item against the final files. Every item receives a status: **Create**, **Skip**, or **Blocked**. A skipped item has a reason. A blocked item identifies the exact missing product fact, photo, or confirmation needed.

A common gallery checklist includes:

1. **Main image:** Product clearly presented on a plain background, with no added promotional graphics.
2. **Feature image:** Verified details or construction explained with short callouts.
3. **Lifestyle image:** Product shown in a realistic context that matches confirmed use.
4. **Dimensions image:** Exact size values and orientation shown consistently.
5. **Scale image:** Product beside a person or reliable size reference.
6. **Detail image:** Close view of texture, finish, components, or a real open state.
7. **Package contents image:** Only items confirmed to be included.
8. **Variant image:** Actual options compared using their own references.
9. **Occasion or gifting image:** Included only when relevant to the product.

The user may also name image treatments such as white background, natural shadow, premium studio, comparison, no overlay text, or square composition. These are handled as requested creative outputs. Each requested treatment gets its own file unless the user asks for a combined layout or smaller set. Similar concepts are not silently dropped simply because they seem redundant.

Not every product can support every slot. If no confirmed variant photos exist, the skill should not invent variants. It can mark that slot blocked and continue with the other images. A missing package list does not need to prevent a lifestyle image from being made.

## 5. It plans, prompts, and generates images

The skill can produce a written plan with scene prompts and overlay copy, or it can generate finished image files when the user asks for images. For an image request, it should not stop at suggestions: it should create separate files for all applicable, supported slots in scope.

Where possible, the preferred method is to preserve the real product pixels and improve the background or scene around them. This can mean cutting out the actual item and compositing it into a generated room, protecting the product while editing its background, or using an actual product photo for a close-up. Preserving the product itself is often more reliable than asking an image model to redraw every detail.

Sometimes the user explicitly wants an AI-rendered product image. In that case, the skill can create a rendering based on the supplied reference, but it labels the result as a draft. The generated scene may alter small words, illustration details, seams, proportions, colors, or component placement. It should not be presented as a verified photograph or guaranteed upload-ready creative.

For text-heavy infographics, the skill can draft concise factual callouts and use a layout with clear space for them. Exact words, dimensions, and units need checking. If precision matters, editable text should be added in a design tool rather than trusting generated lettering inside the image.

## 6. It keeps dimensions and scale consistent

When a seller supplies dimensions, the skill creates a Scale Lock. It records units, orientation, and rounding, then carries those values consistently into dimension graphics and scale scenes. For a landscape object listed as 8 inches wide by 6 inches high, the width and height labels should remain in that orientation throughout the project.

The skill does not treat a number in an inspiration graphic as confirmed product measurement. It asks for confirmation or a physical measurement if the requested image depends on an unverified dimension. It also avoids placing size labels on image types where they do not belong, such as a clean main image.

For human scale scenes, a model or known object should provide a believable reference without distorting the product. If the person is only decorative and does not clarify scale or use, they may not be needed. For products intended for children, any scene involving a minor should be age-appropriate and show attentive adult supervision where relevant.

## 7. It asks focused questions only when needed

The skill reviews the conversation and supplied material first. It should not ask the seller to repeat facts already given or plainly visible. It asks concise questions only when a missing answer could change the image or make its claim misleading.

Examples include exact dimensions for a measurement graphic, package contents for a “what's included” image, actual variant photos for a comparison, intended age for a human-use scene, or confirmed instructions for a product demonstration. If only one slot depends on an answer, the other supported slots can proceed while that item is marked blocked.

This keeps the workflow moving and reduces unnecessary intake. It also gives the seller a precise reason for each question: what image is affected and what evidence would unblock it.

## 8. It supports Amazon A+ Content

A+ Content is a separate product-detail-page deliverable, not an extra gallery image. The skill can help build a page narrative, choose relevant modules, draft factual headlines and body copy, plan module images, and prepare a handoff manifest linking each planned module to its copy and image files.

A typical narrative may introduce the product, explain verified differentiators, show use or context, present dimensions or details, and include a comparison or brand story only when the seller has supporting facts and related products. The sequence should fit the actual item rather than forcing a preset template.

The skill may ask about marketplace and language, product title or listing URL, brand name and logo, brand tone, confirmed features, target shopper, related ASINs, and whether the seller wants Basic or Premium A+. It should ask only for details that affect the plan. Seller eligibility and module availability can vary, so the seller's account and current Amazon guidance determine what can actually be built.

A+ copy should be scannable and factual. It should not invent certifications, guarantees, review quotes, performance results, compatibility, safety claims, price promotions, or package contents. Module images should be mapped to the correct content area and checked for legible crops on desktop and mobile.

## 9. It can make an HTML preview

When asked for an A+ HTML file, the skill can produce a standalone, responsive web page that previews the proposed content. It can include semantic headings, module text, image placements, alt text, and a simple desktop/mobile layout. The preview helps the seller see the narrative and review copy before transferring it into Seller Central.

The HTML is a review and handoff artifact, not normally a direct upload file for Amazon A+. A+ pages are generally assembled in Seller Central using the modules available to the seller, with their text fields and image uploads. The skill should say this clearly and provide a module-to-file map so the seller knows which text and image belong in each section. If the seller requests both the HTML preview and all images, the preview does not replace the image files.

## 10. It reviews the output and makes a clear handoff

Before reporting completion, the skill compares each generated image with the Accuracy Lock and supplied references. It checks product identity, dimensions, component count, colors, text, claims, packaging, variants, and explicit exclusions. It can flag mismatches and identify which files need revision.

The final folder should be easy to understand. Images should have descriptive filenames, separate files for each planned item, and an accompanying checklist or README. A+ projects should also include a module manifest and the HTML preview if requested. The handoff reports what was created, what was skipped or blocked, and what needs physical-product confirmation before publishing.

The final check is a checklist-to-files comparison: every applicable item marked **Create** must have a saved file. If tool limits or missing evidence prevent completion, the skill should say exactly what remains instead of calling a partial set complete.

## What the skill does not promise

The skill supports creative production and review; it does not guarantee Amazon approval, sales, conversion lift, or compliance with requirements that may have changed. Marketplace image rules, module availability, and export specifications should be checked against current official seller guidance before submission. AI-generated product renderings remain drafts until compared with the physical item. The seller remains responsible for confirming product facts and approving assets.

## A simple way to start

A seller can start by invoking `$amzphoto`, attaching clear photos of the actual item, and saying what they need: a gallery plan, a full image set, an A+ module plan, or an HTML preview. They should include known measurements, intended use, included items, real variants, and any important “must show” or “must not show” constraints. The skill can then identify what is known, ask only for missing details that matter, build the complete checklist, create the requested outputs, and leave a clear review package.

The goal is a repeatable workflow: understand the product, lock the facts, plan the full set, create every supported deliverable, review the results, and hand them back in a form that is easy to check and use.
