# ts

> Add timestamps to every line from `stdin`.
> More information: <https://manned.org/ts>.

- Add a timestamp to the beginning of each line:

`{{command}} | ts`

- Add timestamps with microsecond precision:

`{{command}} | ts "{{%b %d %H:%M:%.S}}"`

- Add [i]ncremental timestamps with microsecond precision, starting from zero:

`{{command}} | ts -i "{{%H:%M:%.S}}"`

- Convert existing timestamps in a text file (eg. a log file) into [r]elative format:

`cat {{path/to/file}} | ts -r`
