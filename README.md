**TTTTTT: Template Transpiler to Torvald's Tech Tales** is just an another bespoke blogging framework.

## Setup

1. Put python codes to somewhere that user `wwwrun` can reach and execute.
2. Add webhook endpoint that calls the python code.
3. Set up a git repository that contains original articles. Add webhook accordingly.
4. Set up filesystem such that files from step 3. is fed through `BLOG_ROOT/articles`.
5. Modify `blog_config.py` as needed.

When setup is complete, simply pushing to articles repository will trigger HTML pages compiling.
