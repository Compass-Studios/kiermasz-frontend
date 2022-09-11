<script lang="ts">
    import { Router, Route, Link } from "svelte-routing";
    import LoginPage from "../routes/login/LoginPage.svelte";
</script>

<header>
    <Router>
        <nav>
            <ul>
                <li>
                    <Link to="logowanie">
                        logowanie
                    </Link>
                </li>
            </ul>
        </nav>
        <Route path="logowanie">
            <LoginPage />
        </Route>
    </Router>
</header>

<style type="text/scss">

</style>