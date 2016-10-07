# Breakpoints/Media Queries for SCSS

####I know there are lots of Media Queries SCSS files out there which is more advanced feature than this. But i made this Breakpoints to make it easier for Beginners.

#### It is as easy as including just a single line of code in your existing SCSS files.

#### First of all, i will explain about what are the resolutions i used in this Breakpoints.

1. lg (aka) Large Screen has width of '75em' which is '1200px',
2. md (aka) Medium Screen has width of '62em' which is '992px',
3. sm (aka) Small Screen has width of '48em' which is '768px',
4. xs (aka) eXtra Small Screen has width of '30em' which is '480px'.

#### So let's come to the point, how to use in the SCSS file,

#### Place this 'breakpoints.scss' in your CSS or SCSS folder and import using following command,

'@import "breakpoints";'

#### or append with your existing import.

#### Now include your desired breakpoint to get it done. That's All.

### Syntax,

''''
@include your-breakpoint {
  //your code here;
}
''''

### An Example,

''''
@include xs {
  font-size: 10px;
}
''''

#### That's all, if your include above code in your SCSS file. Then devices with minimum width of 480px will have font size of 10px.

##That's All Folks!

## Thank you.
