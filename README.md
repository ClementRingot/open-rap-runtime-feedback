# Open RAP Runtime — feedback

Bug reports, feature requests and questions about
[Open RAP Runtime](https://clementringot.github.io/RAP-Transpiler/): the `rapt` command, the VS Code
extension and the applications it generates (OData V4 service, RAP managed runtime, OpenUI5 UI).

**[Report a bug](../../issues/new?template=bug_report.yml)** ·
**[Request a feature](../../issues/new?template=feature_request.yml)** ·
or use the [feedback form of the website](https://clementringot.github.io/RAP-Transpiler/feedback.html),
which fills in the version and the environment for you.

Before writing, have a look at the
[known gaps](https://clementringot.github.io/RAP-Transpiler/docs/known_gaps.html) (with their
workarounds) and at the [open issues](../../issues).

When you report a problem, please include:

- the version (`rapt --help` prints it on its first line, or the version of the VS Code extension);
- the smallest RAP sources that show it (CDS, BDEF, behavior pool…), or the output of
  `rapt check <project>`;
- what you expected, and what happened instead.

Do not paste secrets (tokens, passwords, `.env` files) nor confidential sources: this repository is
public.

Open RAP Runtime is not affiliated with SAP SE. SAP, ABAP, Fiori and SAP BTP are trademarks of
SAP SE.
