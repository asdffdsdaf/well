<script>
    import {Button, Checkbox, TextInput} from "carbon-components-svelte";
    import ArrowRight16 from "carbon-icons-svelte/lib/ArrowRight16";
</script>

<style lang="scss">
  @import "src/scss/spacing.scss";
</style>

<div class="bx--grid bx--grid--full-width">
    <div class="s-auth-panel bx--col-md-4 bx--col-lg-4">
        <div class="s-login-top">
            <h2 class="bx--type-productive-heading-04">
                <span>Log in</span>
            </h2>
            <p>
                <span>Don't have an account?</span>
                <a href="/register">Create an account</a>
            </p>
        </div>
        <tr>
        <div class="s-login-text-field">
            <TextInput labelText="User name" placeholder="Enter user name..."/>
        </div>
        <div class="s-login-continue-button">
            <Button icon={ArrowRight16}>Continue</Button>
        </div>
        </tr>
        <div>
            <Checkbox labelText="Remember Account"/>
        </div>
    </div>
</div>