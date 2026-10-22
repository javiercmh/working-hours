# Working Hours

An offline-first working-hours tracker for [App²](https://github.com/javiercmh/appapp), built with plain HTML, CSS and JavaScript.

Track shifts and breaks, calculate overtime, mark entries transferred to a spreadsheet, and configure end-of-day reminders. Reminders require App² on Android; browser previews work only while the page is open.

## Use with App²

Import this public repository in App² using its GitHub import feature:

https://github.com/javiercmh/working-hours

Import it as a new subapp. This repository starts with empty shift records and default settings. It does not contain or update any existing phone workspace.

## Browser preview

Use Python 3, with no extra dependencies:

```sh
python3 dev_server.py
```

Open http://localhost:8888. The development server listens on localhost and writes to this checkout's `data/` files; use a disposable copy for experiments. Do not expose the development server to the Internet.

See [AGENTS.md](AGENTS.md) for app behavior and [PACKAGING.md](PACKAGING.md) for the App² runtime contract.

## License and origin

MIT; see [LICENSE](LICENSE). Extracted from `examples/working_hours/` in App². The previous example icon is omitted because its source and redistribution licence are unknown. App² can use its default icon.
