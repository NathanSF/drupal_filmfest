<?php
?>

  <span style="width: 600px; display: block; margin-left: auto; margin-right: auto;" id="page-wrapper">
    <div id="page">
  
      <span id="header">
  
        <?php if ($logo): ?>
          <a style="width: 600px;" href="<?php print $front_page; ?>" title="<?php print t('Home'); ?>" rel="home" id="logo" class="logo">
            <img src="<?php print $logo; ?>" alt="<?php print t('Home'); ?>" />
          </a>
        <?php endif; ?>
          <?php print render($page['header']); ?>

    </span> <!-- /#header -->
      <span id="main-wrapper">
      <?php print $messages; ?>
    
   
        
<div id="content-wrap" class="container content-wrap clearfix">
        
        <span id="main" class="main">

          <span id="content" class="column clear-fix">
    
            <span class="page-content content-column section">
              <span class="gutter">
                <a id="main-content"></a>
                <?php if ($tabs): ?><div class="tabs"><?php print render($tabs); ?></div><?php endif; ?>
                <?php print render($page['content']); ?>
                <?php print $feed_icons; ?>
              </span>
            </span><!-- /.section .content .gutter -->
          </span> <!-- /#content -->
    
        </span><!-- /#main -->
        
    
      </span> <!-- /#main-wrapper -->
  
</div><!-- /#content-main -->
  
    </div><!-- /#page -->
    
    <div id="footer">
      <?php if ($page['bottom_one'] || $page['bottom_two'] || $page['bottom_three'] || $page['bottom_four']): ?>
      <div id="bottom" class="container clearfix">
    <table width="600px">

<tr>
<td style="float: left;">
              <?php print render($page['bottom_one']); ?>
</td>
<td>
              <?php print render($page['bottom_two']); ?>
</td>
</tr>
      </table>

    
        <?php if ($page['bottom_four']): ?>
          <div class="region bottom bottom-four<?php print ' bottom-'. $bottom; ?>">
            <div class="gutter">
              <?php print render($page['bottom_four']); ?>
            </div>
          </div>
        <?php endif; ?>
      </div>
      <?php endif; ?>
      <div class="container section footer">
        <?php print render($page['footer']); ?>
        <div id="levelten"><?php print l('Drupal Theme', 'http://www.leveltendesign.com/'); ?> by LevelTen Interactive</div>
      </div><!-- /.section -->
    </div> <!-- /#footer -->
    
  </span> <!-- /#page-wrapper -->
