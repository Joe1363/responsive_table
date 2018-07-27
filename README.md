# Responsive Tables

Responsive Table is a lightweight, pure CSS solution for displaying responsive tables using display table.

Responsive Table comes in a base version no with additional styling and one with simple styling provided.

## Usage

Add Resp Table to your project. Resp Table uses classes structured like a simplified HTML table.

Begin with the "resp_table" class.

    <div class="resp_table">
      ...
    </div>

From here add div class "rt_tr" to function as your table tr and divs with class "rt_th" as your table th.

    <div class="resp_table">
        <div class="rt_tr">
            <div class="rt_th">Header 1</div>
            <div class="rt_th">Header 2</div>
            <div class="rt_th">Header 3</div>
        </div>
        ...
    </div>

For the content, add "rt_tr" containing a divs "rt_m_th" that will function as your mobile header and a div "rt_tdc" to contain the content.

      ...
      <div class="rt_tr">
          <div class="rt_td">
              <div class="rt_m_th">Header 1</div>
              <div class="rt_tdc">Content 1</div>
          </div>
          <div class="rt_td">
              <div class="rt_m_th">Header 2</div>
              <div class="rt_tdc">Content 2</div>
          </div>
          <div class="rt_td">
              <div class="rt_m_th">Header 3</div>
              <div class="rt_tdc">Content 3</div>
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
            <div class="rt_tdc">Content Block 1</div>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 2</div>
            <div class="rt_tdc">Content Block 2</div>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 3</div>
            <div class="rt_tdc">Content Block 3</div>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 4</div>
            <div class="rt_tdc">Content Block 4</div>
        </div>
      </div>

      <div class="rt_tr">
        <div class="rt_td">
            <div class="rt_m_th">Header 1</div>
            <div class="rt_tdc">Content Block 5</div>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 2</div>
            <div class="rt_tdc">Content Block 6</div>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 3</div>
            <div class="rt_tdc">Content Block 7</div>
        </div>
        <div class="rt_td">
            <div class="rt_m_th">Header 4</div>
            <div class="rt_tdc">Content Block 8</div>
        </div>
      </div>
    </div>
