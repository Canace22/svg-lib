<template>
  <div class="hello">
    <icon-base width="100" height="80">
      <icon-circle r="5"></icon-circle>
    </icon-base>
    <icon-base>
      <icon-comment fill="#fff" stroke="rgb(102, 100, 100)"></icon-comment>
    </icon-base>
    <icon-base>
      <icon-comment-normal fill="#fff" stroke="rgb(102, 100, 100)"></icon-comment-normal>
    </icon-base>
    <icon-base>
      <icon-notify fill="#fff" stroke="rgb(102, 100, 100)"></icon-notify>
    </icon-base>
    <icon-base>
      <icon-search fill="#fff" stroke="rgb(102, 100, 100)"></icon-search>
    </icon-base>
    <icon-base>
      <icon-share fill="#fff" stroke="rgb(102, 100, 100)"></icon-share>
    </icon-base>
    <icon-base>
      <icon-collect fill="#fff" stroke="rgb(102, 100, 100)"></icon-collect>
    </icon-base>
    <icon-base>
      <icon-thanks fill="#fff" stroke="rgb(102, 100, 100)"></icon-thanks>
    </icon-base>
    <icon-base>
      <icon-arrow-right stroke="rgb(102, 100, 100)"></icon-arrow-right>
    </icon-base>
    <icon-base>
      <icon-close stroke="rgb(102, 100, 100)"></icon-close>
    </icon-base>
    <icon-base>
      <icon-setting fill="rgb(102, 100, 100)"></icon-setting>
    </icon-base>
  </div>
</template>

<script>
import IconBase from './icons/IconBase'
import IconCircle from './icons/IconCircle'
import IconComment from './icons/IconComment'
import IconNotify from './icons/IconNotify'
import IconSearch from './icons/IconSearch'
import IconCommentNormal from './icons/IconCommentNormal'
import IconShare from './icons/IconShare'
import IconCollect from './icons/IconCollect'
import IconThanks from './icons/IconThanks'
import IconArrowRight from './icons/IconArrowRight'
import IconClose from './icons/IconClose'
import IconSetting from './icons/IconSetting'

export default {
  name: 'HelloWorld',
  components: {
    IconBase,
    IconCircle,
    IconComment,
    IconCommentNormal,
    IconNotify,
    IconSearch,
    IconShare,
    IconCollect,
    IconThanks,
    IconArrowRight,
    IconClose,
    IconSetting
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
