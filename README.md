# miro

   View markdown on console using ANSI escape code

## install


   ```
   cpan install Text::VisualWidth::PP
   ```

   Copy **miro** to directory thought path.

   If you need code syntax high light, Install source-highlight.
   like this.

   ```
   # apt install source-highlight
   ```

   If you need sixel or iTrem2 image protocol

   ```
   # apt install libsixel-bin
   # apt install imgcat
   ```

## usage

   ```
   $ miro <markdown file>
   ```

   using with less

   ```
   $ miro -l <markdown file> | less -R
   ```


## samples

   ![test1](https://github.com/tksmiura/miro/blob/master/test/test_screenshot1.png)
   ![test2](https://github.com/tksmiura/miro/blob/master/test/test_screenshot2.png)
