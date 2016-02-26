# Three-Two-One CSS Grid
A simple flexbox grid system. It allows for a full-width responsive layout by thirds, quarters, and halves. @media breaks at 900px and 500px.
## Basic Usage
![example image](/example/chrome_2016-02-25_21-43-04.png)
```
<div class="container base">
    <div class="fourth stretch">
        <h3 class="h-center">1/4th width</h3>
    </div>
    <div class="half stretch">
        <h3 class="h-center">1/2 width</h3>
        <div class="container">
            <div class="third">
                <h4>1/6th</h4>
                <p>Text..</p>
            </div>
            <div class="third">
                <h4>1/6th</h4>
            </div>
            <div class="third">
                <h4>1/6th</h4>
            </div>
        </div>
    </div>
    <div class="fourth stretch">
        <h3 class="h-center">1/4th width</h3>
    </div>
    <div class="whole">
        <h3 class="h-center">Whole</h3>
    </div>
</div>
```
#### Resizing
![Resize example gif](/example/2016-02-25_22-00-44.gif)
```
<div class="container base">
      <div class="fourth md-third sm-fourth">
          <h3 class="h-center">Text..</h3>
      </div>
      <div class="fourth md-two-thirds sm-three-fourths">
          <h3 class="h-center">Text..</h3>
      </div>
      <div class="fourth md-half sm-whole">
          <h3 class="h-center">Text..</h3>
      </div>
      <div class="fourth md-half sm-half">
          <h3 class="h-center">Text..</h3>
      </div>
      <div class="whole  sm-half">
          <h3 class="h-center">Text..</h3>
      </div>
  </div>
  ```
  ## 3-2-1?
  Three-two-one was born out of a need for a light grid system using flexible boxes (with no other styling attached).
  Flex-items can be re-ordered and rearranged as the size of a page changes, allowing a greater flexibility in styling webpages that
  will be viewed on multiple screen sizes. Flexboxes also allow for vertical or horizontal arrangements.
  
  ### Current Functionality
  + Full width base container.
  + Percentage-based widths, assignable at breakpoints(900px, 500px).
  
  ### Planned Functionality
  + Flexbox order assignable at breakpoints
  + Basic column sizing
  
  ## Contributers Welcome
