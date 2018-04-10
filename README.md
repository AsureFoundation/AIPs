# AIPs

Asure Improvement Proposals (AIPs) describe standards for the Asure platform, including core protocol specifications, client APIs, and contract standards.

# Contributing

 1. Review [AIP-1](AIPS/aip-1.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your EIP to your fork of the repository. There is a [template AIP here](aip-X.md).
 4. Submit a Pull Request to Asure's [AIPs repository](https://github.com/AsureFoundation/AIPs).

Your first PR should be a first draft of the final AIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new AIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the AIP as a whole.

If your AIP requires images, the image files should be included in a subdirectory of the `assets` folder for that EIP as follow: `assets/aip-X` (for aip **X**). When linking to an image in the AIP, use relative links such as `../assets/aip-X/image.png`.

When you believe your AIP is mature and ready to progress past the draft phase, you should do one of two things:

 - **For a Standards Track AIP of type Core**, ask to have your issue added to [the agenda of an upcoming All Core Devs meeting](https://github.com/AsureFoundation/pm/issues), where it can be discussed for inclusion in a future release. If implementers agree to include it, the AIP editors will update the state of your AIP to 'Accepted'.
 - **For all other AIPs**, open a PR changing the state of your AIP to 'Final'. An editor will review your draft and ask if anyone objects to its being finalised. If the editor decides there is no rough consensus - for instance, because contributors point out significant issues with the AIP - they may close the PR and request that you fix the issues in the draft before trying again.

# AIP status terms
* **Draft** - an AIP that is open for consideration
* **Accepted** - an AIP that is planned for immediate adoption, i.e. expected to be included in the next release.
* **Final** - an AIP that has been adopted in a previous release.
* **Deferred** - an AIP that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent release.
