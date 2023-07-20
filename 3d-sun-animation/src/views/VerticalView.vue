<template>
  <div class="verticalview">
    <div id="data">
      <a class="sun" title="sun" href="#sunspeed">Sun</a>
      <a class="mercury" title="mercury" href="#mercuryspeed">Mercury</a>
      <a class="venus active" title="venus" href="#venusspeed">Venus</a>
      <a class="earth" title="earth" href="#earthspeed">Earth</a>
      <a class="mars" title="mars" href="#marsspeed">Mars</a>
      <a class="jupiter" title="jupiter" href="#jupiterspeed">Jupiter</a>
      <a class="saturn" title="saturn" href="#saturnspeed">Saturn</a>
      <a class="uranus" title="uranus" href="#uranusspeed">Uranus</a>
      <a class="neptune" title="neptune" href="#neptunespeed">Neptune</a>
    </div>
    <div id="universe" class="scale-stretched">
      <div id="galaxy">
        <div id="solar-system" class="earth">
          <div id="mercury" class="orbit">
            <div class="pos">
              <div class="planet">
                <dl class="infos">
                  <dt>Mercury</dt>
                  <dd><span></span></dd>
                </dl>
              </div>
            </div>
          </div>
          <div id="venus" class="orbit">
            <div class="pos">
              <div class="planet">
                <dl class="infos">
                  <dt>Venus</dt>
                  <dd><span></span></dd>
                </dl>
              </div>
            </div>
          </div>
          <div id="earth" class="orbit">
            <div class="pos">
              <div class="orbit">
                <div class="pos">
                  <div class="moon"></div>
                </div>
              </div>
              <div class="planet">
                <dl class="infos">
                  <dt>Earth</dt>
                  <dd><span></span></dd>
                </dl>
              </div>
            </div>
          </div>
          <div id="mars" class="orbit">
            <div class="pos">
              <div class="planet">
                <dl class="infos">
                  <dt>Mars</dt>
                  <dd><span></span></dd>
                </dl>
              </div>
            </div>
          </div>
          <div id="jupiter" class="orbit">
            <div class="pos">
              <div class="planet">
                <dl class="infos">
                  <dt>Jupiter</dt>
                  <dd><span></span></dd>
                </dl>
              </div>
            </div>
          </div>
          <div id="saturn" class="orbit">
            <div class="pos">
              <div class="planet">
                <div class="ring"></div>
                <dl class="infos">
                  <dt>Saturn</dt>
                  <dd><span></span></dd>
                </dl>
              </div>
            </div>
          </div>
          <div id="uranus" class="orbit">
            <div class="pos">
              <div class="planet">
                <dl class="infos">
                  <dt>Uranus</dt>
                  <dd><span></span></dd>
                </dl>
              </div>
            </div>
          </div>
          <div id="neptune" class="orbit">
            <div class="pos">
              <div class="planet">
                <dl class="infos">
                  <dt>Neptune</dt>
                  <dd><span></span></dd>
                </dl>
              </div>
            </div>
          </div>
          <div id="sun">
            <dl class="infos">
              <dt>Sun</dt>
              <dd><span></span></dd>
            </dl>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import "../assets/css/css for sideview&verticalview/verticalview.css";
</style>
