# http-prompt-scripts
Contains scripts for http-promt. Allows you to make requests from the commandline.

# Installation
You need to use my branch of http-prompt if my [pull request]() wasn't merged.

```bash
pip install git+https://github.com/HappyKadaver/http-prompt.git@file_upload_support
```

# Usage

```bash
http-prompt

> source exercise_post
> post


> source submission_post
> submission[exercise_id]=<exercise_id>
> post
```

If you online want to authenticate you can use `source authenticate`.
If you need to register you can use `source register`

For further information see the manual of [http-prompt](http://http-prompt.com/) and [http-pie](https://httpie.org/).