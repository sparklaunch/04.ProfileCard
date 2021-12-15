<div id="details">
    <div id="followers">
        <p>80K</p>
        <p>Followers</p>
    </div>
    <div id="likes">
        <p>803K</p>
        <p>Likes</p>
    </div>
    <div id="photos">
        <p>1.4K</p>
        <p>Photos</p>
    </div>
</div>

<style>
    #details {
        padding: 30px;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
    }
    #details > div {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    #details > div > p:first-child {
        font-weight: 700;
        font-size: 22px;
        color: rgb(43, 43, 58);
        margin-bottom: 5px;
    }
    #details > div > p:last-child {
        color: rgb(126, 128, 131);
        font-size: 14px;
        letter-spacing: 1px;
    }
</style>
