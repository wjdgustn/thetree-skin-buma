<template>
    <footer :class="bulma('footer')">
        <div :class="bulma('container')">
            <div :class="bulma('content has-text-centered')">
                <p>
                    <span v-html="$store.state.page.data.copyright_text" />
                    <span v-html="$store.state.config['wiki.footer_text']" />

                    theseed-skin-buma by LiteHell, the tree engine by hyonsu <br />
                    theseed-skin-buma is distributed under
                    <a href="https://www.gnu.org/licenses/gpl-3.0.html">GNU General Public License Version 3</a>
                </p>
            </div>
        </div>
    </footer>
</template>

<script setup>
import bulma from '../src/bulma';
</script>
