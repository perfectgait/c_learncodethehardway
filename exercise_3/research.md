Escape Sequences
---------------------
http://en.wikipedia.org/wiki/Escape_sequences_in_C

\a                  Alarm (Beep, Bell)
\b                  Backspace
\f                  Formfeed
\n                  Newline (Line Feed)
\r                  Carriage Return
\t                  Horizontal Tab
\v                  Vertical Tab
\\                  Backslash
\'                  Single quotation mark
\"                  Double quotation mark
\?                  Question mark
\0                  Null (string terminator)
\ and a newline     Macro continuation: ignore the \ and the newline
\nnn                Octal representation
\xhh                Hexadecimal representation
\uhhhh              Unicode character

Format Sequences
--------------------
http://www.cplusplus.com/reference/cstdio/printf/

%d or %i    Signed decimal integer
%u          Unsigned decimal integer
%o          Unsigned octal
%x          Unsigned hexidecimal integer
%X          Unsigned hexidecimal integer (uppercase)
%f          Decimal floating point, lowercase
%F          Decimal floating point, uppercase
%e          Scientific notation (mantissa/exponent), lowercase
%E          Scientific notation (mantissa/exponent), uppercase
%g          Use the shortest representation: %e or %f
%G          Use the shortest representation: %E or %F
%a          Hexidecimal floating point, lowercase
%A          Hexidecimal floating point, uppercase
%c          Character
%s          String of characters
%p          Pointer address
%n          Nothing printed
            The corresponding argument must be a pointer to a signed int.
            The number of characters written so far is stored in the pointed location
%%          %
