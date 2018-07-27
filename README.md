# Resp Tables

Resp Table is a lightweight, pure CSS solution for displaying responsive tables using display table.

Resp Table comes in a base version no with additional styling and one with simple styling provided.

## Usage

Add Resp Table to your project. Resp Table uses classes structured like a simplified HTML table.

Begin with the "resp_table" class.

    <div class="resp_table">
      ...
    </div>

From here add div "rt_tr" with the first containing divs with "rt_th".

    <div class="resp_table">
        <div class="rt_tr">
            <div class="rt_th">Header 1</div>
            <div class="rt_th">Header 2</div>
            <div class="rt_th">Header 3</div>
        </div>
        ...
    </div>

For the content, add "rt_tr" containing a div "rt_m_th" that will function as your mobile header and a span "rt_td" to contain the content.

      ...
      <div class="rt_tr">
          <div class="rt_td">
              <div class="rt_m_th">Header 1</div>
              <span>Content 1</span>
          </div>
          <div class="rt_td">
              <div class="rt_m_th">Header 2</div>
              <span>Content 2</span>
          </div>
          <div class="rt_td">
              <div class="rt_m_th">Header 3</div>
              <span>Content 3</span>
          </div>
      </div>
      ...

Resp Table will collapse to mobile view at a screen width of 860px by default. Adjust as needed.


Full example:

    <div class="resp_table">
      <div class="rt_tr">
        <div class="rt_th">Header 1</div>
        <div class="rt_th">Header 2</div>
        <div class="rt_th">Header 3</div>
        <div class="rt_th">Header 4</div>
      </div>

      <div class="rt_tr">
        <div class="rt_td">
            <div class="rt_m_th">Header 1</div>
            <span>Content Block 1</span>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 2</div>
            <span>Content Block 2</span>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 3</div>
            <span>Content Block 3</span>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 4</div>
            <span>Content Block 4</span>
        </div>
      </div>

      <div class="rt_tr">
        <div class="rt_td">
            <div class="rt_m_th">Header 1</div>
            <span>Content Block 5</span>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 2</div>
            <span>Content Block 6</span>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 3</div>
            <span>Content Block 7</span>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 4</div>
            <span>Content Block 8</span>
        </div>
      </div>
    </div>
