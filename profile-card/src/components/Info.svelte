<div id="info">
    <div id="name">
        <p>Victor Crest</p>
        <p>26</p>
    </div>
    <div id="address">
        <p>London</p>
    </div>
</div>

<style>
    #info {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
        height: 60px;
        margin-top: -36px;
        margin-bottom: 30px;
    }
    #name {
        width: 160px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: rgb(43, 44, 56);
    }
    #name > p:first-child {
        font-weight: 700;
        font-size: 22px;
    }
    #name > p:last-child {
        font-size: 18px;
    }
    #address > p {
        color: rgb(101, 102, 108);
    }
</style>
