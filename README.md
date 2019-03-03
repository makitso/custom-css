# common.css
Style changes to webtrees 2.0 for all themes
There are several steps necessary in order to use a common.css file in the 2.0 version of webtrees.
Step # 1 - this style sheet into folder /public/css
Step # 2 - add a <link to the stylesheet to file default.phtml located in folder /resuurces/views/layouts
  
  <link rel="stylesheet" href="<?= e(asset('css/common.css')) ?>">
  
  This link must reside after the standard stylesheets and will look like this:
  
  <link rel="stylesheet" href="<?= e(asset('css/vendor.min.css')) ?>">
        <?php foreach (app(ModuleThemeInterface::class)->stylesheets() as $stylesheet) : ?>
            <link rel="stylesheet" href="<?=  e($stylesheet) ?>">
        <?php endforeach ?>
			<link rel="stylesheet" href="<?= e(asset('css/common.css')) ?>">
        <?= View::stack('styles') ?>
